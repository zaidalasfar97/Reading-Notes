# Resposive Overview 
### Resonsive web design is the practice of building a website suitable to work on every device and every screen size ,no matter how large or small , mobile or desktop . Responsive web design is focused around providing an intuitive and gratifying experience for everyone .

# Responsive vs. Adaptive vs. Mobile 
### Responsive generally means to react quickly and positivelt to any change , while adaptive means to easily modified for a new purpose or situation , such as change . With responsive design websites continually and fluidly change based on different factors , such as viewport width , while adaptive websites are built to a group of preset factors .

# Mobile generally means to build a separate website commonly on a new domain solely for mobile users . 

# Flexible Layouts:

# Responsive web design is broken down into three main components:
#### 1-Flexible layouts.
#### 2-Media queries.
#### 3-Flexible media.


### Flexible layouts, is the practice of building the layout of a website with a flexible grid, capable of dynamically resizing to any width. Flexible grids are built using relative length units, most commonly percentages or em units. These relative lengths are then used to declare common grid property values such as width, margin, or padding.

### Flexible layouts do not advocate the use of fixed measurement units, such as pixels or inches. Reason being, the viewport height and width continually change from device to device. Website layouts need to adapt to this change and fixed values have too many constraints. Fortunately, Ethan pointed out an easy formula to help identify the proportions of a flexible layout using relative values.

### The formula is based around taking the target width of an element and dividing it by the width of it’s parent element. The result is the relative width of the target element.


# Media Queries:
### Media queries were built as an extension to media types commonly found when targeting and including styles. Media queries provide the ability to specify different styles for individual browser and device circumstances, the width of the viewport or device orientation for example. Being able to apply uniquely targeted styles opens up a world of opportunity and leverage to responsive web design.

# All About Floats :
### Float is a CSS positioning property. To understand its purpose and origin, we can look to print design. In a print layout, images may be set into the page such that text wraps around them as needed. This is commonly and appropriately called “text wrap”. Here is an example of that.

### In web design, page elements with the CSS float property applied to them are just like the images in the print layout where the text flows around them. Floated elements remain a part of the flow of the web page. This is distinctly different than page elements that use absolute positioning. Absolutely positioned page elements are removed from the flow of the webpage, like when the text box in the print layout was told to ignore the page wrap. Absolutely positioned page elements will not affect the position of other elements and other elements will not affect them, whether they touch each other or not.

# Float values :
#### 1-Right.
#### 2-Left.
#### 3-None.
#### 4-Inherit.