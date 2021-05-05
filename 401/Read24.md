# Hashtables :
## What is a Hashtable? 
#### 1-Hash - A hash is the result of some algorithm taking an incoming string and converting it into a value that could be used for either security or some other purpose. In the case of a hashtable, it is used to determine the index of the array.
#### 2-Buckets - A bucket is what is contained in each index of the array of the hashtable. Each index is a bucket. An index could potentially contain multiple key/value pairs if a collision occurs.
#### 3-Collisions - A collision is what happens when more than one key gets hashed to the same location of the hashtable.

## Why do we use them?
#### Hold unique values
#### Dictionary
#### Library

## Hashing is a technique that is used to uniquely identify a specific object from a group of similar objects.

## In hashing, large keys are converted into small keys by using hash functions. The values are then stored in a data structure called hash table. The idea of hashing is to distribute entries (key/value pairs) uniformly across an array. Each element is assigned a key (converted key). By using that key you can access the element in O(1) time. Using the key, the algorithm (hash function) computes an index that suggests where an entry can be found or inserted.

## To achieve a good hashing mechanism, It is important to have a good hash function with the following basic requirements:

#### 1-Easy to compute: It should be easy to compute and must not become an algorithm in itself.

#### 2-Uniform distribution: It should provide a uniform distribution across the hash table and should not result in clustering.

#### 3-Less collisions: Collisions occur when pairs of elements are mapped to the same hash value. These should be avoided.

### In computing, a hash table (hash map) is a data structure that implements an associative array abstract data type, a structure that can map keys to values. A hash table uses a hash function to compute an index, also called a hash code, into an array of buckets or slots, from which the desired value can be found. During lookup, the key is hashed and the resulting hash indicates where the corresponding value is stored.

