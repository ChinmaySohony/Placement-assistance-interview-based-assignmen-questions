# Placement-assistance-interview-based-assignmen-questions
#### Chinmay Sohony

## HTML Questions :

<br>

### 1) `<!DOCTYPE html>` is it a tag of html? If not, what is it and why do we use it?
<br>

##### Answer :
```
Yes, <!DOCTYPE html> is indeed a tag in HTML. However, it is not a regular HTML element like <div>
or <p>. Instead, it is called a document type declaration (DTD) and it is used to specify the version of
HTML or XHTML that the document is written in.
The <!DOCTYPE html> declaration is used at the very beginning of an HTML document to inform the
web browser about the version of HTML being used. In HTML5, <!DOCTYPE html> is the
recommended and simplest doctype declaration, indicating that the document is written in HTML5.
The purpose of the doctype declaration is to ensure that the web browser renders the document in
the correct way. Different versions of HTML have different rules and syntax, so specifying the
doctype helps the browser understand how to interpret and display the content of the document. It
also helps ensure backward compatibility with older browsers.
By using <!DOCTYPE html>, you are telling the browser to treat the document as an HTML5
document, which is the latest version of HTML and is widely supported by modern web browsers.
  ```
  <br>
  
### 2) Explain Semantic tags in html? And why do we need it?

<br>

##### Answer :

```
Semantic tags in HTML are a set of elements that provide meaning and structure to the content
within a web page. These tags describe the type of content they enclose, allowing search engines,
screen readers, and other web technologies to better understand and interpret the information.
Semantic tags help improve accessibility, maintainability, and search engine optimization (SEO) of
web pages.Overall, semantic tags enhance both the human and machine interpretation of web content,
resulting in improved accessibility, SEO, and code maintainability.
```

<br>

### 3) Differentiate between HTML Tags and Elements?

<br>

##### Answer :

```
HTML Tags and Elements are closely related but have distinct meanings:
HTML Tags: Tags are the building blocks of HTML markup. They are used to define the structure and
elements of an HTML document. Tags are enclosed in angle brackets (< >) and appear as opening
and closing pairs. For example, <p> is an opening tag, and </p> is a closing tag. Tags indicate the
beginning and end of an element and define its purpose and behavior.
HTML Elements: Elements are made up of tags and the content they enclose. An HTML element
consists of an opening tag, the content within the element, and a closing tag. The content can be
text, other nested elements, or both. For example, the element <p>Hello, World!</p> consists of the
opening tag <p>, the content "Hello, World!", and the closing tag </p>. The element represents a
paragraph in HTML.
In summary, tags are used to define the beginning and end of an element, while elements
encompass both the tags and the content they enclose. HTML tags are like containers, and HTML
elements are the actual content within those containers.
```

<br>

### 4) Build Your Resume using HTML only

<br>

##### Answer :
```
answer file :Html question no 4
```
<br>



### 5) Write Html code so that it looks like the given image

<br>

##### Answer :
```
Answer file:html question no 5
<br>
```


### 6) What are some of the advantages of HsTML5 over its previous versions?

<br>

##### Answer :
```
HTML5, the latest version of the Hypertext Markup Language, introduced several advancements and
advantages over its previous versions. Here are some key advantages of HTML5:
Rich Multimedia Support: HTML5 introduced native support for audio and video elements,
eliminating the need for third-party plugins like Flash. This simplifies the integration and playback of
multimedia content, making it more accessible and efficient.
Canvas Element: HTML5 introduced the <canvas> element, which allows for dynamic, scriptable
rendering of graphics and animations directly within the browser without the need for external
plugins. This provides greater flexibility and interactivity in creating visual elements on the web.
Improved Semantics: HTML5 introduced new semantic elements such as <header>, <nav>, <footer>,
and <article>, which provide a clearer structure to web content. These semantic elements enhance
accessibility, search engine optimization, and code readability by describing the purpose and
meaning of different sections within a webpage.
Enhanced Form Controls: HTML5 introduced new input types, such as date, time, email, URL, and
range, which provide improved user experience and better input validation. Additionally, HTML5
introduced form validation APIs, enabling client-side validation without the need for JavaScript.
Offline and Storage Capabilities: HTML5 introduced features like the Application Cache and Local
Storage, enabling web applications to work offline and store data locally. This allows users to
continue using web apps even when they are not connected to the internet and provides a smoother
user experience.
Improved Performance: HTML5 incorporates optimizations and improvements to enhance the
overall performance of web pages. It includes features like async and defer attributes for script
loading, which improve page loading times, and optimized rendering algorithms that enhance the
speed and efficiency of web browsers.
Mobile-Friendly and Responsive Design: HTML5 offers better support for mobile devices and
responsive design. It includes features like media queries for detecting device characteristics and the
<meta> viewport tag for controlling the layout and scaling of web content on different screen sizes.
Backward Compatibility: HTML5 was designed with backward compatibility in mind. Older HTML
markup will continue to work in HTML5, ensuring that existing web pages and applications built with
previous versions can still be utilized without major modifications.
These are some of the key advantages that HTML5 brings over its previous versions. Its features and
improvements contribute to better multimedia support, enhanced semantics, improved form
controls, offline capabilities, performance optimizations, mobile-friendliness, and backward
compatibility.
```


### 7) Create a simple Music player using html only

<br>

#### Answer :
```
Answer file :html question no 6
 
```
<br>

### 8) What is the difference between `<figure>` tag and `<img>` tag?

<br>

#### Answer :
```
  The <figure> tag and the <img> tag serve different purposes and are used in different contexts:
<img> tag: The <img> tag is used to embed an image within an HTML document. It is a self-closing
tag and does not have any content. It requires the src attribute to specify the path or URL of the
image file and typically includes the alt attribute for providing alternative text that describes the
image. The <img> tag is primarily used to display a standalone image on a web page.
  
```

<br>


### 9) What’s the difference between html tag and attribute and give example of some global attributes?

<br>

#### Answer :

```
The HTML tag and attribute are two different concepts within HTML:
HTML Tag: An HTML tag represents an element in an HTML document. It defines the structure and
functionality of the content within the document. Tags are enclosed in angle brackets (< >) and can
be either opening tags, self-closing tags, or closing tags. Examples of HTML tags include <div>, <p>,
<h1>, <img>, etc. HTML tags define the elements that make up the structure of a webpage.
HTML Attribute: An HTML attribute provides additional information about an HTML element.
Attributes are added within the opening tag of an HTML element to modify its behavior or provide
extra details. They are composed of a name-value pair. The attribute name specifies the property or
characteristic, while the attribute value provides the corresponding value for that property.
Attributes can be applied to various HTML elements to customize their behavior and appearance.
Examples of HTML attributes include src, alt, href, class, id, style, etc.
Here are some examples of global attributes, which can be applied to most HTML elements:
class: Specifies one or more class names to associate with an element, allowing CSS and JavaScript to
target and style the element.
Example: <div class="container">
id: Specifies a unique identifier for an element, which can be used to target the element with CSS or
JavaScript.
Example: <p id="my-paragraph">
style: Defines inline CSS styles to apply to an element.
Example: <h1 style="color: red;">Heading</h1>
title: Provides additional information about an element when hovering over it.
Example: <a href="#" title="Click here">Link</a>
data-*: Allows custom data attributes to be added to elements, which can be accessed via JavaScript
for various purposes.
Example: <div data-custom-attribute="value">
aria-*: Used to define accessibility-related attributes, providing additional information to assistive
technologies and screen readers.
Example: <button aria-label="Close">X</button>
These global attributes can be applied to various HTML elements to customize their behavior,
appearance, or accessibility features. It's important to note that some attributes are specific to
certain elements, while global attributes can be used across different elements.
  ```

<br>


### 10) build Table which looks like the given image

<br>

#### Answer :
```
  Answer file:html question no 10
  ```
  <br>


## CSS Questions :

<br>

### 1) Whats Box Model in CSS & Which CSS Properties are part of it ?

<br>

#### Answer :

```
  The box model is a fundamental concept in CSS (Cascading Style Sheets) that describes how
elements are rendered and how their dimensions and spacing are calculated. It consists of several
properties that define the content area, padding, border, and margin of an element.
The CSS properties that are part of the box model are:
Content: The actual content of an element, such as text or an image. The content area is controlled
by the width and height properties.
Padding: The space between the content area and the element's border. Padding can be set using
the padding property or individual properties like padding-top, padding-right, padding-bottom, and
padding-left.
Border: The border surrounding the element's content and padding. The border can be set using the
border property or individual properties like border-width, border-style, and border-color.
Margin: The space outside the element, creating the gap between adjacent elements. Margin can be
set using the margin property or individual properties like margin-top, margin-right, margin-bottom,
and margin-left.

  ```

<br>


### 2) What are the Different Types of Selectors in CSS & what are the advantages of them?

<br>

#### Answer :

```
  There are many selectors are present in css. first one is Element Selectors, it's Select elements based on their HTML tag name. Class Selectors, it's Select elements based on their assigned class attribute. ID Selectors, it's Select a specific element based on its assigned ID attribute. Attribute Selectors, it's Select elements based on their attribute values. Pseudo-classes and Pseudo-elements: Select elements based on specific states or conditions or target specific parts of an element.
```

<br>


### 3) What is VW/VH & How its different from PX?

<br>

#### Answer :

```
  VW (Viewport Width) and VH (Viewport Height) are CSS units that are relative to the size of the
viewport, which is the visible portion of the browser window.
VW (Viewport Width): The VW unit represents a percentage of the viewport's width. 1 VW is equal
to 1% of the viewport width. For example, if the viewport width is 1000 pixels, 1 VW is equivalent to
10 pixels.
VH (Viewport Height): The VH unit represents a percentage of the viewport's height. 1 VH is equal to
1% of the viewport height. For example, if the viewport height is 800 pixels, 1 VH is equivalent to 8
pixels.
The key difference between VW/VH and PX (pixels) is that VW and VH are relative units that scale
based on the size of the viewport, while pixels (PX) are absolute units that represent a fixed size.
Using VW and VH units can be beneficial in creating responsive and fluid layouts that adapt to
different screen sizes. For example, you can set an element's width to 50 VW, and it will always
occupy 50% of the viewport width regardless of the device or screen size.
On the other hand, pixels (PX) are fixed units that maintain a consistent size regardless of the
viewport. If you set an element's width to 200 pixels, it will always have a width of 200 pixels,
regardless of the viewport size.
VW and VH units are particularly useful for creating responsive designs that adjust dynamically
based on the available screen space. They provide a way to size elements proportionally to the
viewport, allowing for better flexibility and adaptability in different viewing environments.
  ```

<br>


### 4) Whats difference between Inline, Inline Block and block ?

<br>

#### Answer :

```
  The differences between inline, inline-block, and block display properties in CSS relate to how
elements are rendered and how they interact with other elements on the page:
Inline: Elements displayed as inline do not start on a new line and only take up as much width as
necessary to contain their content. They flow alongside each other horizontally, and their height and
width are determined by their content. Examples of inline elements are <span>, <a>, <strong>,
<em>, etc.
Inline-block: Elements displayed as inline-block have characteristics of both inline and block
elements. They flow alongside each other horizontally like inline elements, but they also respect
width, height, padding, and margins like block elements. This means you can set width and height
values, apply margins and padding, and have them affect the layout without forcing a line break.
Examples of inline-block elements are <img>, <input>, and elements styled with display: inline-block.
Block: Elements displayed as block start on a new line and take up the entire width available by
default. They create a block-level box, which means they have line breaks before and after them,
and can have margins, padding, and width/height set. Examples of block elements are <div>, <p>,
<h1> to <h6>, <section>, etc.
  ```

<br>


### 5)How is Border-box different from Content Box?
  <br>

#### Answer :

```
  The difference between border-box and content-box is related to how the width and height of an
element are calculated and how the box model properties (content, padding, border, and margin)
affect the overall size of the element.
Content-box: The content-box is the default box-sizing property value. With content-box, the width
and height of an element only include the content area. In other words, any padding, border, or
margin applied to the element is added to the specified width and height. This means that the total
size of the element will be the sum of its content width/height, padding width/height, and border
width/height.
```

<br>


### 6) What’s z-index and How does it Function ?

<br>

#### Answer :

```
  z-index is a CSS property that controls the stacking order of positioned elements on the z-axis
(depth) of a web page. It specifies the order in which elements are stacked or layered in relation to
each other. Elements with a higher z-index value will appear in front of elements with a lower value.
Here's how z-index functions:
Default Stacking Order: By default, elements have a z-index value of auto. Elements are rendered in
the order they appear in the HTML markup, with later elements appearing on top of earlier ones.
Positioned Elements: The z-index property only applies to positioned elements, i.e., elements with a
CSS position value of relative, absolute, or fixed. It does not have any effect on non-positioned
elements.
Stacking Context: Each positioned element creates a stacking context. The z-index property applies
within the stacking context of an element. An element with a higher z-index value within its stacking
context will appear in front of elements with lower values.
Higher Values = Closer to the Viewer: The stacking order is determined by the numeric z-index value.
The element with the highest z-index appears in front of other elements within the same stacking
context. Negative values can also be used to position elements behind others.
Parent-Child Relationship: When elements are nested, the z-index property of child elements is
relative to the stacking context of their parent. If a parent element has a higher z-index value than its
child, the child element cannot appear in front of the parent.
It's important to note that z-index only affects elements within the same stacking context. If two
elements are in different stacking contexts, their z-index values do not directly compare to each
other.
Using z-index, you can control the visual layering and stacking order of elements on a web page. It
allows you to position elements in front of or behind other elements, creating depth and visual
hierarchy in your design.
  
```


<br>
  
  
  ### 7)Difference between absolute and relative and sticky and fixed position explain with example.
  <br>
  #### Answer :
  
  ```
  The positioning properties in CSS, such as absolute, relative, sticky, and fixed, allow you to control
the placement and behavior of elements on a web page. Here's a breakdown of each:
Relative Positioning:
With position: relative, an element is positioned relative to its normal position in the document flow.
The element still occupies its original space in the layout, and other elements are not affected by its
positioning.
You can use properties like top, bottom, left, and right to offset the element from its original
position.
Example:
css

.box {
 position: relative;
 top: 20px;
 left: 10px;
}
In this example, the .box element is positioned 20 pixels down and 10 pixels to the right from its
normal position.
Absolute Positioning:
With position: absolute, an element is positioned relative to its nearest positioned ancestor, or the
document if there is no positioned ancestor.
The element is taken out of the normal document flow and does not leave a gap where it would
have been.
It is positioned based on the values of the properties top, bottom, left, and right, relative to its
nearest positioned ancestor or the document.
Example:
css

.box {
 position: absolute;
 top: 50px;
 left: 100px;
}
In this example, the .box element is positioned 50 pixels down and 100 pixels to the right from its
nearest positioned ancestor or the document.
Sticky Positioning:
With position: sticky, an element is positioned based on its normal position in the document flow
until a specified threshold is met, and then it becomes sticky and remains fixed at that position.
Sticky elements are positioned based on the values of top, bottom, left, and right relative to their
containing block.
Example:
css

.box {
 position: sticky;
 top: 20px;
}
In this example, the .box element is positioned 20 pixels from the top of its containing block. When
the user scrolls past the threshold defined by the .box element's parent or nearest scrollable
ancestor, it becomes sticky and remains fixed at that position.
Fixed Positioning:
With position: fixed, an element is positioned relative to the viewport, regardless of scrolling.
The element is taken out of the normal document flow and does not move when the page is
scrolled.
It is positioned based on the values of top, bottom, left, and right relative to the viewport.
Example:
css

.box {
 position: fixed;
 top: 20px;
 right: 30px;
}
In this example, the .box element is positioned 20 pixels from the top and 30 pixels from the right of
the viewport. It remains fixed at that position, even when the page is scrolled.
These positioning properties provide flexibility in controlling the layout and behavior of elements on
a web page, allowing you to achieve various visual effects and interactive designs.
  ```
   
  <br>
  
  ### 8)Build Periodic Table as shown in the below image
  <br>
  
  #### Answer:
  ```
  Answer file: CSS question no 8
  ```
  <br>

### 9) Build given layout using grid or flex see below image for reference

<br>

#### Answer :
```
Answer file: CSS question no 9 
```
<br>


### 10) Build Responsive Layout both desktop and mobile and Tablet, see below image for reference ?

<br>

#### Answer :
```
Answer file : CSS-Question-10
```
<br>

### 12) What are Pseudo class in CSS & How its different From Pseudo Elements?

<br>
#### Answer:
```
Pseudo-classes and pseudo-elements are both selectors in CSS that allow you to target specific
elements based on various conditions. Here's a brief explanation of each:
Pseudo-classes:
Pseudo-classes are used to select and style elements based on certain states or conditions.
They start with a colon (:) followed by the name of the pseudo-class.
Pseudo-classes select elements that are in a specific state or meet a certain condition, such as being
hovered over, being the first child, or being visited.
Examples of pseudo-classes include :hover, :active, :focus, :first-child, :last-child, :nth-child(), etc.
Pseudo-elements:
Pseudo-elements are used to style a specific part of an element or insert content before or after an
element.
They start with a double colon (::) followed by the name of the pseudo-element.
Pseudo-elements allow you to create styling and layout effects that target specific parts of an
element, such as the first letter, the first line, or creating a decorative element before or after the
content of an element.
Examples of pseudo-elements include ::first-letter, ::first-line, ::before, ::after, etc.
In summary, pseudo-classes are used to select elements based on states or conditions, while
pseudo-elements are used to target specific parts of an element or insert content before or after an
element. Both pseudo-classes and pseudo-elements provide additional flexibility in styling and
manipulating elements based on different criteria.
```
<br>

## Javascript questions:
<br>

### 1)What is Hoisting in Javascript ?
<br>

### Answer:

```
Hoisting is a behavior in JavaScript where variable and function declarations are moved to the top of
their containing scope during the compilation phase, before the code is executed. This means that
regardless of where variables and functions are declared in the code, they are treated as if they are
declared at the beginning of their scope.
However, it is important to note that only the declarations are hoisted, not the initializations or
assignments. This means that while the declarations are moved to the top, the actual values
assigned to variables or the function definitions are left in their original positions.
Here are a few key points to understand about hoisting:
Variable Hoisting:
Variable declarations (using var) are hoisted to the top of their scope.
The variable is created with an initial value of undefined until it is assigned a value.
Example:
javascript

console.log(myVariable); // undefined
var myVariable = 10;
Function Hoisting:
Function declarations (not function expressions) are hoisted to the top of their scope.
The entire function, including its body, is hoisted.
Example:
javascript

sayHello(); // "Hello!"
function sayHello() {
 console.log("Hello!");
}
Hoisting does not occur with block-scoped declarations (let and const). They are hoisted to the top
of the block scope, but they are not accessible until they are declared.
It's important to be aware of hoisting in JavaScript to avoid potential confusion and unintended
behavior. It is considered good practice to declare variables and functions at the beginning of their
respective scopes to improve code readability and avoid unexpected hoisting-related issues.
```
<br>

### 2)What are different higher order functions in JS? What is the difference between .map() and .forEach()?

<br>

### Answer:
```
The main differences between map() and forEach() are:
Return Value: map() returns a new array with the transformed elements, while forEach() does not
return anything. It simply iterates over the array and performs an action on each element.
Immutability: Since map() returns a new array, it does not modify the original array. forEach(), on the
other hand, does not create a new array and directly modifies the existing array.
Chaining: Because map() returns a new array, you can chain multiple array methods after it.
forEach(), being void, cannot be chained directly.
Use Case: If you need to transform each element of an array and obtain a new array, map() is more
suitable. If you simply want to loop over an array and perform an action for each element, forEach()
is sufficient.
It's important to choose the appropriate higher-order function based on your specific needs and the
desired outcome of your code.
```

<br>

### 3)Explain Event bubbling and Event Capturing in JavaScript with suitable examples.

<br>
### Answer:
```
Event bubbling and event capturing are two mechanisms used by JavaScript to handle events that
occur on nested elements. They describe the order in which events are propagated through the
DOM hierarchy.
Event Bubbling:
In event bubbling, the event is first captured and handled by the innermost element and then
propagated up the DOM tree to the outermost element. This means that the event starts at the
target element and bubbles up through its ancestors.
Here's an example to illustrate event bubbling:
html

<div id="outer">
 <div id="inner">
 <button id="button">Click me</button>
 </div>
</div>
<script>
 const button = document.getElementById('button');
 const inner = document.getElementById('inner');
 const outer = document.getElementById('outer');
 button.addEventListener('click', () => {
 console.log('Button clicked');
 });
 inner.addEventListener('click', () => {
 console.log('Inner div clicked');
 });
 outer.addEventListener('click', () => {
 console.log('Outer div clicked');
 });
</script>
When you click the button, the event starts at the button element, triggers the button's click event
handler, and then bubbles up to the inner div and finally to the outer div. The output in the console
will be:
css

Button clicked
Inner div clicked
Outer div clicked
Event Capturing:
In event capturing, the event is first captured and handled by the outermost element and then
propagated down the DOM tree to the innermost element. This means that the event starts at the
outermost element and captures the event as it moves towards the target element.
To demonstrate event capturing, we can modify the previous example as follows:
javascript

// ...
button.addEventListener('click', () => {
 console.log('Button clicked');
}, { capture: true });
inner.addEventListener('click', () => {
 console.log('Inner div clicked');
}, { capture: true });
outer.addEventListener('click', () => {
 console.log('Outer div clicked');
}, { capture: true });
// ...
By setting the capture option to true in the addEventListener method, the events will be captured
during the capturing phase instead of the bubbling phase. The output in the console will now be:
css

Outer div clicked
Inner div clicked
Button clicked
Note that by default, event listeners use the bubbling phase (capture: false). However, you can
explicitly specify the capturing phase by setting capture: true when attaching an event listener.
Understanding event bubbling and event capturing is crucial for handling events correctly in nested
DOM structures and designing event-driven JavaScript applications.
```

<br>

### 4)What is function currying with example?
<br>
### Answer:
```
Function currying is a technique in JavaScript where a function with multiple arguments is
transformed into a sequence of functions, each taking a single argument. It allows you to partially
apply a function by fixing some of its arguments, creating a new function that can be called with the
remaining arguments later.
Here's an example to illustrate function currying:
javascript
Copy code
// Original function with multiple arguments
function multiply(a, b, c) {
 return a * b * c;
}
// Curried version of the multiply function
function curriedMultiply(a) {
 return function(b) {
 return function(c) {
 return a * b * c;
 };
 };
}
// Calling the curried function
const result = curriedMultiply(2)(3)(4);
console.log(result); // Output: 24
In the above example, we have a multiply function that takes three arguments and returns their
multiplication. We then define a curriedMultiply function that takes the first argument a and returns
a new function that takes the second argument b and returns another function that takes the third
argument c and finally performs the multiplication.
By calling curriedMultiply(2)(3)(4), we are able to calculate the result of multiplying 2, 3, and 4,
which is 24. The function calls are chained, where each subsequent function call returns a new
function until all the arguments are provided.
Function currying allows for more flexibility and reusability in function composition. It enables us to
create specialized versions of functions by providing some arguments in advance and then reusing
those partially applied functions later.
```

<br>

### 5)Explain execution context diagram of following code snippets, use white board to draw.
<br>
### Answer:
```
Code Snippet 1:
javascript

console.log('First');
setTimeout(() => console.log('Second'), 0);
console.log('Third');
The execution starts from the global execution context.
The first statement console.log('First') is executed, and it logs 'First' to the console.
The setTimeout function is called with a callback function and a delay of 0 milliseconds. This
schedules the execution of the callback function to occur later, but not immediately.
The statement console.log('Third') is executed, and it logs 'Third' to the console.
The execution of the current context completes, and the event loop starts checking for any
scheduled tasks.
The event loop detects the scheduled task from setTimeout with a delay of 0 milliseconds. Since the
delay is 0, the callback function is moved to the event queue.
The event loop then checks the event queue, finds the callback function, and moves it to the call
stack.
The callback function () => console.log('Second') is executed, and it logs 'Second' to the console.
The output in the console will be:
sql

First
Third
Second
Code Snippet 2:
javascript
Copy code
console.log('First');
function secondCall() {
 console.log('Second');
}
setTimeout(secondCall, 2000);
setTimeout(() => console.log('Third'), 0);
console.log('Third');
The execution starts from the global execution context.
The first statement console.log('First') is executed, and it logs 'First' to the console.
The secondCall function is defined but not executed.
The setTimeout function is called with secondCall as the callback function and a delay of 2000
milliseconds. This schedules the execution of secondCall after a delay of 2000 milliseconds.
Another setTimeout function is called with an arrow function () => console.log('Third') as the callback
function and a delay of 0 milliseconds. This schedules the execution of the arrow function to occur
later, but not immediately.
The statement console.log('Third') is executed, and it logs 'Third' to the console.
The execution of the current context completes, and the event loop starts checking for any
scheduled tasks.
After 2000 milliseconds, the event loop detects the scheduled task from the first setTimeout with a
delay of 2000 milliseconds. The callback function secondCall is moved to the event queue.
The event loop then checks the event queue, finds the callback function, and moves it to the call
stack.
The secondCall function is executed, and it logs 'Second' to the console.
The event loop continues to check the event queue and finds the arrow function from the second
setTimeout with a delay of 0 milliseconds.
The arrow function () => console.log('Third') is moved to the call stack and executed, logging 'Third'
to the console.
The output in the console will be:
sql
First
Third
Second
Third
```

<br>

### 6)What are promises? What are the different states of a promise? Support your answer with an example where you need to create your own promise.

<br>
### Answer:
```
Promises are a feature in JavaScript that allow you to handle asynchronous operations in a more
organized and readable way. They represent the eventual completion (or failure) of an asynchronous
operation and allow you to attach callbacks to handle the results.
A promise can be in one of the following three states:
Pending: The initial state of a promise. It means that the asynchronous operation associated with the
promise is still in progress and has not yet been fulfilled or rejected.
Fulfilled: The state of a promise when the asynchronous operation is successfully completed. It
means that the promise has resolved with a value.
Rejected: The state of a promise when the asynchronous operation encounters an error or fails. It
means that the promise has been rejected with a reason or an error object.
Here's an example of creating and using a custom promise:
javascript

function fetchData() {
 return new Promise((resolve, reject) => {
 setTimeout(() => {
 const data = 'Some data';
 // Simulating a successful async operation
 resolve(data);
 // Simulating an error
 // reject('Error occurred');
 }, 2000);
 });
}
// Using the custom promise
fetchData()
 .then((result) => {
 console.log('Promise resolved:', result);
 })
 .catch((error) => {
 console.log('Promise rejected:', error);
 });
In the above example, the fetchData function returns a custom promise. Within the promise
constructor, there is a simulated asynchronous operation using setTimeout. After 2 seconds, the
promise is resolved with the data value.
You can use the promise by chaining .then() to handle the resolved state and .catch() to handle the
rejected state. If the promise is resolved, the result will be logged to the console. If the promise is
rejected, the error will be logged.
By utilizing promises, you can effectively handle asynchronous operations, maintain code readability,
and handle both success and error cases in a more structured manner.
```
<br>

### 7)What is ‘this’ keyword in JavaScript? explain with an example & create.

<br>
### Answer:
```
In JavaScript, the this keyword refers to the context in which a function is called. It is a special
keyword that allows you to access and manipulate the properties and methods of the object that the
function is bound to. The value of this is determined dynamically at runtime based on how the
function is invoked.
The behavior of this can vary depending on the context in which it is used. Here are a few examples
to illustrate its usage:
Example 1: Global Scope
javascript
Copy code
console.log(this); // Output: Window (global object in browser)
In the global scope (outside of any function), this refers to the global object. In a browser
environment, the global object is usually Window.
Example 2: Object Method
javascript
Copy code
const person = {
 name: 'John',
 greet: function() {
 console.log(`Hello, ${this.name}!`);
 }
};
person.greet(); // Output: Hello, John!
In this example, this inside the greet method refers to the person object. It allows us to access the
name property of the person object using dot notation.
Example 3: Constructor Function
javascript
Copy code
function Person(name) {
 this.name = name;
}
const john = new Person('John');
console.log(john.name); // Output: John
When a function is used as a constructor function with the new keyword, this refers to the newly
created object. In this example, this inside the Person constructor refers to the object being
constructed, and we assign the name property to that object.
Example 4: Event Handler
javascript
Copy code
const button = document.getElementById('myButton');
button.addEventListener('click', function() {
 console.log(this); // Output: the button element
});
In an event handler function, such as the one attached to a button click event, this refers to the
element that triggered the event. In this example, this refers to the button element itself.
It's important to note that the value of this is not determined by how or where a function is defined,
but rather by how it is called or invoked. The same function can have different values of this
depending on how it is called.
Creating a custom example:
javascript
Copy code
const car = {
 brand: 'Toyota',
 getModel: function() {
 return this.brand + ' Camry';
 }
};
console.log(car.getModel()); // Output: Toyota Camry
In this example, we have an object car with a brand property and a getModel method. Inside the
getModel method, this refers to the car object, allowing us to access the brand property and
concatenate it with the string ' Camry'. The output will be 'Toyota Camry'.
```
<br>

### 8)Explain event loop Call Stack Callback queue and Micro Task queue in Your Words .

<br>

### Answer:
```
Call Stack:
The call stack is a data structure in JavaScript that keeps track of the execution context of functions.
Whenever a function is called, a new frame (execution context) is pushed onto the stack. When a
function completes its execution, its frame is popped off the stack. The call stack operates on a "last
in, first out" (LIFO) principle.
Callback Queue:
The callback queue, also known as the task queue, is a queue that holds callback functions waiting to
be executed. Callback functions are typically generated as a result of asynchronous operations, such
as a timer, network request, or event listener. When an asynchronous operation completes, its
corresponding callback function is placed in the callback queue.
Microtask Queue:
The microtask queue, also known as the job queue, is a queue that holds microtasks. Microtasks are
tasks with higher priority than regular callback functions. They are usually scheduled for execution
after the current JavaScript execution context finishes, but before the next rendering or user
interaction. Promises and certain APIs, like queueMicrotask, add tasks to the microtask queue.
Event Loop:
The event loop is a mechanism in JavaScript that manages the execution of code, including handling
asynchronous operations and ensuring smooth interaction with the browser environment. Its main
purpose is to constantly monitor the call stack, callback queue, and microtask queue to determine
which tasks can be executed next.
Here's a simplified overview of how these components interact:
Initially, the call stack is empty.
As JavaScript code is executed, functions are pushed onto the call stack.
When an asynchronous operation is encountered, such as a setTimeout or an AJAX request, the
associated callback function is sent to the callback queue.
After the call stack is empty, the event loop checks the microtask queue.
If there are any tasks in the microtask queue, they are executed one by one until the microtask
queue is empty.
Once the microtask queue is empty, the event loop checks the callback queue.
If there are any tasks in the callback queue, the event loop moves them to the call stack for
execution.
This process continues, with the event loop constantly monitoring the call stack, microtask queue,
and callback queue.
In simpler terms, the event loop keeps an eye on the call stack and queues. It ensures that tasks in
the callback queue and microtask queue are executed in the appropriate order, preventing the
browser from becoming unresponsive.
```

