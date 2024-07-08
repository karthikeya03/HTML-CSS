# Learning HTML and CSS : 

## Introduction :

> To create and view websites, you need:

1. A **Web Browser**: Allows you to view and interact with your website.
2. A **Code Editor**: Helps you write the code for your website.

## General Strategy in HTML :

1. First write a `HTML` for the required output
2. Then style it with `css`

## HTML: HyperText Markup Language

> HTML is the standard language used to create websites. It consists of a series of elements that define the structure and content of web pages.

## Lession 1. HTML Basics :

### 1. File Naming

- **Save As**: filename.html

### 2. Syntax :

- **Syntax**: The rules of writing code.
- **Grammar**: The structure and order of elements in HTML.

### 3. HTML Elements :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/mg%2001.png)

### 4. Button :

```
<button> Hello </button>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image1.png)

### 5. Paragraph :

```
<p> This is a paragraph of text. </p>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image2.png)

### 6. Link to Another Website :

```
<a href="https://www.youtube.com"> Link to YouTube </a>
```

- **<a>**: Anchor element used to create links.
- **href**: Attribute specifying the URL of the linked page.
- **target**: Attribute specifying where to open the linked document.

```
<a href="https://www.youtube.com" target="_blank"> Link to YouTube </a>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image3.png)

### 7. Extra Spaces and New Lines :

> Extra spaces and new lines in HTML are generally ignored.

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image4.jpeg)

### 8. Indentation :

> Indentation helps keep your code readable. Use the `tab` key to indent your code.

### Exercises You Can Practice on HTML :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/1233.png)
![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image6.png)

<br>

# Lession 2. CSS Basics :

**Cascading Style Sheets (CSS)**: Used to change the appearance of HTML elements.

### 1. Applying CSS to Buttons :

```
<button> SUBSCRIBE </button>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/mg2.png)

#### 2. CSS :

```
<style>
button {
  background-color: red;
}
</style>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image7.png)

### 3. CSS Selectors :

> Selectors are used to target HTML elements for styling.

#### Example :

```
<style>
button {
  background-color: red;
  color: white;
  border: none;
  height: 36px;
  width: 100px;
}
</style>
```

### 4. RGB Colors :

> Colors can be defined using RGB (Red, Green, Blue) values.

```
background-color: rgb(255, 0, 0);
```

### 5. Border Radius and Cursor :

- **border-radius**: Defines the roundness of the corners.
- **cursor**: Defines the type of cursor to be displayed.

  ![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image8.png)

### 6. Creating a Join Button :

```html
<button> JOIN </button>
```

```html
<button class="subscribe-button"> SUBSCRIBE </button>
```

code: 
```
.subscribe-button {
  background-color: red;
  color: white;
  border: none;
  height: 36px;
  width: 100px;
}
.join-button {
  background-color: blue;
  color: white;
  border: none;
  height: 36px;
  width: 100px;
  border-radius: 2px;
}
```

### 7. Margins :

- **margin-right**: Adds space to the right of an element.

```
margin-right: 8px;
```

### Exercises You Can Practice on CSS :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image9.png)
![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image10.png)

# Lession 3. Hovers, Transitions, and Shadows :

### 1. Hover :

> A pseudo-class used to define the style of an element when the mouse is over it.

```
.subscribe-button:hover {
  background-color: white;
}
```

### 2. Active :

> Defines the style of an element when it is being clicked.

```
.subscribe-button:active {
  background-color: blue;
}
```

### 3. Opacity :

> Defines the transparency of an element.

```
.subscribe-button:active {
  opacity: 0.3;
}
```

### 4. Transitions :

> Defines the transition effect for properties.

```
transition: opacity 1s;
```

#### Example :

```
.join-button:hover {
  background-color: blue;
  color: white;
}
.join-button:active {
  opacity: 0.7;
}
```

### 5. Shadows :

> In CSS, shadows can enhance the design by adding depth and dimension to elements. The box-shadow property is used to apply shadows to elements such as buttons or divs.

#### Example :

```
.tweet-button {
  box-shadow: 0 0 0 black; /* Takes 4 values */
}
```

> Representatives :
> The box-shadow property takes the following values:

. `Horizontal position: Determines the horizontal offset of the shadow.` <br>
. `Vertical position: Determines the vertical offset of the shadow.` <br>
. `Blur: Specifies the blur radius of the shadow.` <br>
. `Color: Defines the color of the shadow.` <br>

> For instance, if you use `10px 10px 10px black`, the shadow will be positioned `10 pixel`s to the `right`, `10 pixels down from the element`, and have a `blur radius` of `10 pixels`.

Here's an illustration :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/MG3.png)

### 6. RGBA Value :

> The rgba value in CSS is used to define colors with transparency. It is an extension of the RGB color model, where a stands for alpha and represents the opacity level.

#### Example :

```
box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.6);
```

> This code will create a shadow that is 10 pixels to the right, 10 pixels down, with a blur radius of 10 pixels, and the color will be black with 60% opacity.

Here's an illustration :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/mg4.png)

### Exercises You Can Practice on Hovers, Transitions, and Shadows :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/end.png)

# Lession 4. Chrome DevTools & CSS Box Model :

### 1. Dev tools :

> What are the dev tools? :
> `. open` the inspect button to look at the developer tools of any website of your choice
> `. click` on the cursor button on the left most to find different elements adn their css, HTML

![CSS BOX MODEL](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/hello1.png)

### 2. CSS Box model :

> margin & padding is used to define a box model in CSS

#### Example for padding :

```
padding-left : 30px;
padding-top : 20px;
padding-bottom : 30px;
padding-right : 20px;

```

# Understanding Margins, Borders, Padding, and Content in CSS :

> In CSS, the box model is essential for designing and laying out web pages. The following diagram illustrates the relationships between margins, borders, padding, and content:

### 1. Box Model Components :

1. **Content**: `The innermost area where text and images are displayed.` <br>

2. **Padding**: `The space between the content and the border, adding space inside the border.` <br>

3. **Border**: `The line that surrounds the padding and content, forming the element's boundary.` <br>

4. **Margin**: `The outermost space, providing distance between the element and other elements.` <be>

![CSS BOX MODEL](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/hello2.png)

### CSS Example :

```css
.element {
  width: 200px;        /* Content width */
  padding: 10px;       /* Space around content */
  border: 2px solid;   /* Element boundary */
  margin: 15px;        /* Space outside the border */
}
```

> When used padding the text gets automatically adjusted with the box model rather than using height and width.
> It is recommended to use padding

### 2. vertical align :  top : 

> aligns everything to the top

### Exercises You Can Practice DevTools & CSS Box Models on :

![CSS BOX MODEL](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/1.1.png) <br>
![CSS BOX MODEL](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/1.png)

# Lession 5. How to style text :

1. go to supersimple.dev/excercises/text : for text

 ### 1. To add changes to the font :

> changes the font

```
 <style>
     .video.title {
       font-family : arial; // changes the font
       font-size : 30px; // increases or decreases the font size
       font-weight : bold; // changes the font bold
       font-style : italic; // changes to italic
     }
   </style>
   <p class = "video-title" > SOME TEXT </p>
```

### 2. Align the Font :

> Aligning the font adjusts the position of text within an element.
> For example, to center-align text, you can use the `text-align` property in CSS.

```
<style>
  .video-title {
    text-align: center; /* Aligns the text to the center */
  }
</style>
<p class="video-title">SOME TEXT</p>
```

### 3. Width and Line Height :

> Setting the width of a text container can cause the text to wrap to a new line if it exceeds the specified width.
> The line-height property adds vertical spacing between lines of text.
> <br>
> here is the illustration :

![width](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/z.1.png)

### 4. HTML Entity

> HTML entities are used to display reserved characters or symbols in HTML.
> They start with an ampersand (&) and end with a semicolon (;).
> For example, &amp; represents the ampersand symbol (&), and &lt; represents the less-than sign (<).
> <br>

<p>Use &amp; to represent an ampersand (&).</p>
<p>Use &lt; to represent a less-than sign (<).</p>
<p>Use &gt; to represent a greater-than sign (>).</p>

#### Example :

```
<p class="video-stats" 3.4 views `&#183` (HTML entity code for dot)
  Talking Tech and AI With google CEO Sundar Pichai!
  </p>
.video-stats
{
// add desired code
}
```

### 5. Default Paragraph Margins :

> By default, paragraphs come with margin on the top and bottom, which creates space between paragraphs.

### 6. CSS Selector Specificity :

> In CSS, a more specific selector has a higher priority.
> For example, a class name selector is more specific than an element name selector.

```
/* Element name selector */
p {
  color: blue;
}

/* Class name selector */
.highlight {
  color: red;
}
```

<br>

    `Class selector > Name Selector`
<br>
In this example, if a paragraph (<p>) has the class highlight, the text will be red because the class name selector (.highlight) is more specific and takes priority over the element name selector

```
<p class="highlight">This text will be red.</p>
<p>This text will be blue.</p>
```

### 7. Text Decoration :

> The text-decoration property in CSS is used to add decorative elements to text, such as underlines, overlines, and strikethroughs.

Example:

```
.highlight
{
text-decoration : underline;
}
```

### 8. Text element :

> Text elements in HTML are used to format and display text in specific ways. Here are some common text elements:

1. Strong element : creates bold text on the webpage :
   here is the illustration :
   ![strong](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/y.1.png)
2. u element : creates text that is underlined
   here is the illustration :
   ![u](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/y.2.png)

3. span element : give it any class adn style it ourselves :
   `<span> Hello </span>`
   example :

```
   <span class = "span-edit"> The text that has to be edited </span>
   <style>
     .span-edit
     {
   color : red;
     }
   </style>
```

Here is the illustration :
![width](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/y,3.png)

> Output : `The text will be red `

### 9. Add margin to a text element :

> Adding margin to a text element creates space around the element. For example, you can add a left margin to a span element to move it to the right.

```
   <span class = "span-edit"> The text that has to be edited </span>
   <style>
     .span-edit
     {
   color : red;
   margin-left : 20px; // adds margin to the left
     }
   </style>
```

### Exercises You Can Practice on Text Styles :

![width](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/y.4.png)
![width](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/y.5.png)


# Lession 6. The HTML Structure :
> HTML provides the basic structure for web pages. Here's a detailed breakdown:


### 1. Document Type Declaration :
> The `<!DOCTYPE html>` declaration is not an HTML element; it's a special instruction that specifies the HTML version being used. It must be included at the beginning of every HTML document.

```html
<!DOCTYPE html>
```

![width](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/h.1.png)

### 2. HTML Element :

> The `<html>` element is the root element of an HTML page. It wraps all the content on the entire page.

```html
<html>
  <!-- Content of the page goes here -->
</html>
```

### 3. Head Element :

> The `<head>` element contains meta-information about the HTML document, such as the title of the page, links to stylesheets, and metadata.

```html
<head>
  <title>First Website</title>
  <link rel="stylesheet" href="style.css">
</head>
```
![body](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/h.2.png)

### 4. Title Element :

> The `<title>` element defines the title of the HTML document, which appears in the browser's title bar or tab.

```html
<title>First Website</title>
```

### 5. Link Element :

> The `<link>` element is used to link external resources to the HTML document, such as stylesheets (`rel="stylesheet"`).

```html
<link rel="stylesheet" href="style.css">
```

here is the image : 
 ![body](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/h.3.png)

### 6. Body Element :

> The `<body>` element contains all the content that is visible on the web page, including text, images, links, and other elements.

```html
<body>
  <h1>Welcome to My Website</h1>
  <p>This is the content of my website.</p>
</body>
```

### 7. Visible Content :

> All visible elements, such as headings (`<h1>` to `<h6>`), paragraphs (`<p>`), images (`<img>`), links (`<a>`), and more, are placed within the `<body>` element.

### 6. Void Elements :

Void elements in HTML do not have closing tags and are self-closing. Examples include `<img>`, `<link>`, `<br>`, and `<input>`.

```html
<img src="image.jpg" alt="Description">
<br>
<input type="text" placeholder="Enter your name">
```

### 7. Adding Fonts :

> To add custom fonts to your HTML document, use the `<link>` tag to include the font stylesheet in the `<head>` section.

```html
<head>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Roboto', sans-serif;
    }
  </style>
</head>
```
here is the image : 
![font](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/h.11.png)

#### Example :

```html
<!DOCTYPE html>
<html>
<head>
  <title>First Website</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>Welcome to My Website</h1>
  <p>This is the content of my website.</p>
</body>
</html>
```

### Exercises :

Here are some exercises you can practice to solidify your understanding:

![HTML Structure Exercises](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/h.12.png)


# Lesson 7: Images and Text Box :

## Images :

To add an image in HTML, use the `<img>` tag with the `src` attribute specifying the link of the image:

`<img src="(link of image)">`

### Attributes :

1.  **Width and Height**: These attributes can be used to change the size of the image.

    `<img src="(link of image)" width="300" height="200">`

2.  **Object Fit**: This CSS property specifies how the content of a replaced element, such as an `<img>`, should be resized to fit its container.

    - `cover`: The image will be resized to cover the entire container, even if it means cropping the image.

      `img { object-fit: cover; }`

    - `contain`: The image will be resized to be fully contained within the container, maintaining its aspect ratio.

      `img { object-fit: contain; }`

3.  **Object Position**: This CSS property specifies the alignment of the replaced element inside its container.

    - Example: Align the image to the right.

      `img { object-position: right; }`

### Example :

![Image Example](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/hello1.png)

## Input Elements :

### Text Input :

To create a text input field in HTML, use the `<input>` element with the `type` attribute set to `"text"`:

`<input type="text">`

### Checkbox :

To create a checkbox in HTML, use the `<input>` element with the `type` attribute set to `"checkbox"`:

`<input type="checkbox">`

### Placeholder :

The `placeholder` attribute specifies a short hint that describes the expected value of an input field.

![Placeholder Example](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/hello2.png)

## Exercises :

Here are some exercises you can practice:

![Exercise 1](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/hello3.png) ![Exercise 2](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/hello4.png)

# Lesson 8: CSS Display Property :

There are three types of elements in HTML:

1. **Block Elements**: These elements take up the entire line. For example, a paragraph (`<p>`) by default is a block element.
2. **Inline-Block Elements**: Examples include `<img>` and `<input>`. These elements take only the required space but behave like block elements.
3. **Inline Elements**: These elements appear within the line of text.

Here is an example to switch from block to inline-block:

```css
.video-author {
  display: inline-block;
}
```

![Exercise 2](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/e.2.png)

## Exercises :

Here are some exercises you can practice:

![Exercise 1](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/e4.png)

# Lesson 9: The Div Element :

> The `<div>` tag stands for division. An easy way to understand it is as a box. It's a box.

1. A `<div>` is like a paragraph; it is a block element.

## Why is it so useful?

- It can contain any other elements inside.
- We can put any elements in the `<div>`, making them containers.

![dv2](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/a1.png)


## Exercises :

Here are some exercises you can practice:

![Exercise 1](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/m3.png) 
![Exercise 2](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/m2.png) 
![Exercise 3](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/m1.png) 

# Lesson 10: Nested Layouts Technique :

## 1. Introduction to Layout Techniques :

Mastering layouts in HTML is essential for creating visually appealing and well-structured web pages. There are two primary layout techniques:

1. **Vertical Layout**: This technique involves stacking elements on top of each other, similar to a column. It is useful for creating sections or lists where elements follow a top-to-bottom flow.

2. **Horizontal Layout**: This technique places elements side by side, like a row. It is ideal for creating navigation bars, image galleries, or any structure where elements are aligned next to each other.

![Vertical and Horizontal Layouts](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/121.png)

By combining vertical and horizontal layouts, you can create complex and flexible designs suitable for any website.

## 2. Nested Layouts :

Nested layouts involve placing one type of layout inside another, allowing for intricate and multi-dimensional structures. For example, you can have a horizontal layout that contains a vertical layout, which in turn includes multiple horizontal layouts. This nesting capability is powerful for creating advanced web designs.

Here is an example:

![Nested Layout Example](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/123.png)

In this example:
- There is a primary horizontal layout.
- Inside the primary horizontal layout, there is a vertical layout.
- Inside the vertical layout, there are three horizontal layouts.

## 3. Practical Applications :

### 4. Creating a Web Page Header :

1. **Horizontal Layout** for the header section, including the logo and navigation menu.
2. **Vertical Layout** for the navigation items within the header.
3. **Horizontal Layouts** inside the vertical layout for individual navigation links.

### 5. Structuring a Blog Post :

1. **Vertical Layout** for the main content, including the title, images, and paragraphs.
2. **Horizontal Layout** for a gallery of images within the blog post.
3. **Nested Horizontal Layouts** for social media buttons or related articles at the bottom of the post.

## 6. Font Weights :

Font weight refers to the thickness of the characters in a font. Different font weights can be used to create a hierarchy and emphasize important content.

- **Regular Font Weight (400)**: This is the default weight for most text, providing a balanced and readable appearance.
- **Semi-Bold (500)**: Slightly thicker than regular, used to highlight subheadings or important text without being too overpowering.
- **Bold (700)**: Significantly thicker, used for main headings, important notices, or any text that needs to stand out prominently.

## 7. Paragraph Margins :

By default, paragraphs (`<p>`) in HTML have a margin on the top and bottom. This margin creates space between paragraphs, making the text easier to read. The default margins can be adjusted using CSS to suit the design requirements of your web page.

### 8. Example CSS to Adjust Paragraph Margins

```css
p {
  margin-top: 1em;
  margin-bottom: 1em;
}
```

## Exercises :

Here are some exercises you can practice:

![Exercise 1](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/m4.png) 
![Exercise 2](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/m5.png) 
![image](https://github.com/karthikeya03/HTML-CSS/assets/120096427/fa189431-1756-49bd-b946-3a548f0f7f07)


# Lesson 11: CSS grid :

 
