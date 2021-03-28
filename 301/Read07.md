# POST / PUT requests
## A typical JSON POST request might look a little like the following, where we set the Content-Type header field appropriately, and "write" some data, in this case just a JSON string.
# Retrying requests:
### When given the .retry() method, SuperAgent will automatically retry requests, if they fail in a way that is transient or could be due to a flaky Internet connection.

### This method has two optional arguments: number of retries (default 1) and a callback. It calls callback(err, res) before each retry. The callback may return true/false to control whether the request should be retried (but the maximum number of retries is always applied).

### Use .retry() only with requests that are idempotent (i.e. multiple requests reaching the server won't cause undesirable side effects like duplicate purchases).

### All request methods are tried by default (which means if you do not want POST requests to be retried, you will need to pass a custom retry callback).
 
# Setting Accept
### In a similar fashion to the .type() method it is also possible to set the Accept header via the short hand method .accept(). Which references request.types as well allowing you to specify either the full canonicalized MIME type name as type/subtype, or the extension suffix form as "xml", "json", "png", etc. for convenience: