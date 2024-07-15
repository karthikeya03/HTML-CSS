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

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/mg%2001.png)

### 4. Button :

```html
<button> Hello </button>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/image1.png)

### 5. Paragraph :

```html
<p> This is a paragraph of text. </p>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/image2.png)

### 6. Link to Another Website :

```html
<a href="https://www.youtube.com"> Link to YouTube </a>
```

- **<a>**: Anchor element used to create links.
- **href**: Attribute specifying the URL of the linked page.
- **target**: Attribute specifying where to open the linked document.

```
<a href="https://www.youtube.com" target="_blank"> Link to YouTube </a>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/image3.png)

### 7. Extra Spaces and New Lines :

> Extra spaces and new lines in HTML are generally ignored.

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/image4.jpeg)

### 8. Indentation :

> Indentation helps keep your code readable. Use the `tab` key to indent your code.

### Exercises You Can Practice on HTML :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/1233.png)
![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/image6.png)

<br>

# Lession 2. CSS Basics :

**Cascading Style Sheets (CSS)**: Used to change the appearance of HTML elements.

### 1. Applying CSS to Buttons :

```html
<button> SUBSCRIBE </button>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/mg2.png)

#### 2. CSS :

``` html
<style>
button {
  background-color: red;
}
</style>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/image7.png)

### 3. CSS Selectors :

> Selectors are used to target HTML elements for styling.

#### Example :

```html
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

  ![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/image8.png)

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

``` html
margin-right: 8px;
```

### Exercises You Can Practice on CSS :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/image9.png)
![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/image10.png)

# Lession 3. Hovers, Transitions, and Shadows :

### 1. Hover :

> A pseudo-class used to define the style of an element when the mouse is over it.

``` html
.subscribe-button:hover {
  background-color: white;
}
```

### 2. Active :

> Defines the style of an element when it is being clicked.

``` html
.subscribe-button:active {
  background-color: blue;
}
```

### 3. Opacity :

> Defines the transparency of an element.

``` html
.subscribe-button:active {
  opacity: 0.3;
}
```

### 4. Transitions :

> Defines the transition effect for properties.

``` html
transition: opacity 1s;
```

#### Example :

``` html
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

``` html
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

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/MG3.png)

### 6. RGBA Value :

> The rgba value in CSS is used to define colors with transparency. It is an extension of the RGB color model, where a stands for alpha and represents the opacity level.

#### Example :

``` html
box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.6);
```

> This code will create a shadow that is 10 pixels to the right, 10 pixels down, with a blur radius of 10 pixels, and the color will be black with 60% opacity.

Here's an illustration :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/mg4.png)

### Exercises You Can Practice on Hovers, Transitions, and Shadows :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/end.png)

# Lession 4. Chrome DevTools & CSS Box Model :

### 1. Dev tools :

> What are the dev tools? :
> `. open` the inspect button to look at the developer tools of any website of your choice
> `. click` on the cursor button on the left most to find different elements adn their css, HTML

![CSS BOX MODEL](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/hello1.png)

### 2. CSS Box model :

> margin & padding is used to define a box model in CSS

#### Example for padding :

``` html
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

![CSS BOX MODEL](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/hello2.png)

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

![CSS BOX MODEL](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/1.1.png) <br>
![CSS BOX MODEL](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/1.png)

# Lession 5. How to style text :

1. go to supersimple.dev/excercises/text : for text

 ### 1. To add changes to the font :

> changes the font

```css
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

```css
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

![width](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/z.1.png)

### 4. HTML Entity

> HTML entities are used to display reserved characters or symbols in HTML.
> They start with an ampersand (&) and end with a semicolon (;).
> For example, &amp; represents the ampersand symbol (&), and &lt; represents the less-than sign (<).
> <br>

<p>Use &amp; to represent an ampersand (&).</p>
<p>Use &lt; to represent a less-than sign (<).</p>
<p>Use &gt; to represent a greater-than sign (>).</p>

#### Example :

```  html
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

``` css
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

``` html
<p class="highlight">This text will be red.</p>
<p>This text will be blue.</p>
```

### 7. Text Decoration :

> The text-decoration property in CSS is used to add decorative elements to text, such as underlines, overlines, and strikethroughs.

Example:

``` css
.highlight
{
text-decoration : underline;
}
```

### 8. Text element :

> Text elements in HTML are used to format and display text in specific ways. Here are some common text elements:

1. Strong element : creates bold text on the webpage :
   here is the illustration :
   ![strong](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/y.1.png)
2. u element : creates text that is underlined
   here is the illustration :
   ![u](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/y.2.png)

3. span element : give it any class adn style it ourselves :
   `<span> Hello </span>`
   example :

``` css 
   <span class = "span-edit"> The text that has to be edited </span>
   <style>
     .span-edit
     {
   color : red;
     }
   </style>
```

Here is the illustration :
![width](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/y,3.png)

> Output : `The text will be red `

### 9. Add margin to a text element :

> Adding margin to a text element creates space around the element. For example, you can add a left margin to a span element to move it to the right.

``` css
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

![width](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/y.4.png)
![width](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/y.5.png)


# Lession 6. The HTML Structure :
> HTML provides the basic structure for web pages. Here's a detailed breakdown:


### 1. Document Type Declaration :
> The `<!DOCTYPE html>` declaration is not an HTML element; it's a special instruction that specifies the HTML version being used. It must be included at the beginning of every HTML document.

``` html
<!DOCTYPE html>
```

![width](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/h.1.png)

### 2. HTML Element :

> The `<html>` element is the root element of an HTML page. It wraps all the content on the entire page.

``` html
<html>
  <!-- Content of the page goes here -->
</html>
```

### 3. Head Element :

> The `<head>` element contains meta-information about the HTML document, such as the title of the page, links to stylesheets, and metadata.

``` html
<head>
  <title>First Website</title>
  <link rel="stylesheet" href="style.css">
</head>
```
![body](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/h.2.png)

### 4. Title Element :

> The `<title>` element defines the title of the HTML document, which appears in the browser's title bar or tab.

``` html
<title>First Website</title>
```

### 5. Link Element :

> The `<link>` element is used to link external resources to the HTML document, such as stylesheets (`rel="stylesheet"`).

```html
<link rel="stylesheet" href="style.css">
```

here is the image : 
 ![body](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/h.3.png)

### 6. Body Element :

> The `<body>` element contains all the content that is visible on the web page, including text, images, links, and other elements.

``` html
<body>
  <h1>Welcome to My Website</h1>
  <p>This is the content of my website.</p>
</body>
```

### 7. Visible Content :

> All visible elements, such as headings (`<h1>` to `<h6>`), paragraphs (`<p>`), images (`<img>`), links (`<a>`), and more, are placed within the `<body>` element.

### 6. Void Elements :

Void elements in HTML do not have closing tags and are self-closing. Examples include `<img>`, `<link>`, `<br>`, and `<input>`.

``` html
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
![font](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/h.11.png)

#### Example :

``` html
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

![HTML Structure Exercises](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/h.12.png)


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

![Image Example](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/hello1.png)

## Input Elements :

### Text Input :

To create a text input field in HTML, use the `<input>` element with the `type` attribute set to `"text"`:

`<input type="text">`

### Checkbox :

To create a checkbox in HTML, use the `<input>` element with the `type` attribute set to `"checkbox"`:

`<input type="checkbox">`

### Placeholder :

The `placeholder` attribute specifies a short hint that describes the expected value of an input field.

![Placeholder Example](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/hello2.png)

## Exercises :

Here are some exercises you can practice:

![Exercise 1](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/hello3.png) ![Exercise 2](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/hello4.png)

# Lesson 8: CSS Display Property :

There are three types of elements in HTML:

1. **Block Elements**: These elements take up the entire line. For example, a paragraph (`<p>`) by default is a block element.
2. **Inline-Block Elements**: Examples include `<img>` and `<input>`. These elements take only the required space but behave like block elements.
3. **Inline Elements**: These elements appear within the line of text.

Here is an example to switch from block to inline-block:

``` css
.video-author {
  display: inline-block;
}
```

![Exercise 2](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/e.2.png)

## Exercises :

Here are some exercises you can practice:

![Exercise 1](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/e4.png)

# Lesson 9: The Div Element :

> The `<div>` tag stands for division. An easy way to understand it is as a box. It's a box.

1. A `<div>` is like a paragraph; it is a block element.

## Why is it so useful?

- It can contain any other elements inside.
- We can put any elements in the `<div>`, making them containers.

![dv2](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/a1.png)


## Exercises :

Here are some exercises you can practice:

![Exercise 1](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/m3.png) 
![Exercise 2](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/m2.png) 
![Exercise 3](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/m1.png) 

# Lesson 10: Nested Layouts Technique :

## 1. Introduction to Layout Techniques :

Mastering layouts in HTML is essential for creating visually appealing and well-structured web pages. There are two primary layout techniques:

1. **Vertical Layout**: This technique involves stacking elements on top of each other, similar to a column. It is useful for creating sections or lists where elements follow a top-to-bottom flow.

2. **Horizontal Layout**: This technique places elements side by side, like a row. It is ideal for creating navigation bars, image galleries, or any structure where elements are aligned next to each other.

![Vertical and Horizontal Layouts](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/121.png)

By combining vertical and horizontal layouts, you can create complex and flexible designs suitable for any website.

## 2. Nested Layouts :

Nested layouts involve placing one type of layout inside another, allowing for intricate and multi-dimensional structures. For example, you can have a horizontal layout that contains a vertical layout, which in turn includes multiple horizontal layouts. This nesting capability is powerful for creating advanced web designs.

Here is an example:

![Nested Layout Example](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/123.png)

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

``` css
p {
  margin-top: 1em;
  margin-bottom: 1em;
}
```

## Exercises :

Here are some exercises you can practice:

![Exercise 1](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/m4.png) 
![Exercise 2](https://raw.github.com/karthikeya03/HTML-CSS/JustImages/m5.png) 

# Lesson 11: CSS Grid :

In this lesson, we will learn about CSS Grid, which allows for perfectly aligned horizontal layouts by using rows and columns.

### 1. What is a Grid? :
> A grid is a layout that has rows and columns. Here are some visual examples:
![image](https://github.com/karthikeya03/HTML-CSS/assets/120096427/467d3066-4736-478c-a8f6-a1d05b699239)

#### Example of a 2 by 3 Grid (2 rows, 3 columns) :

![image](https://github.com/karthikeya03/HTML-CSS/assets/120096427/e460846e-b599-4089-b9f9-2c25c82d1ebe)

> This image shows a grid with 2 rows and 3 columns. Each cell in the grid can contain content, and the grid structure helps in organizing this content.

#### Example of a 1 by 2 Grid (1 row, 2 columns) :

![image](https://github.com/karthikeya03/HTML-CSS/assets/120096427/06b9c99b-20be-46f2-b8be-2cdd81ef39a1)

> This image shows a grid with 1 row and 2 columns. It demonstrates how the grid layout can be adjusted to fit different content needs.

### 2. Creating a Simple Grid :

To create a simple grid, you can use the following CSS:

#### Example Code:

``` html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple Grid</title>
    <style>
        .grid-container {
            display: grid;
            grid-template-columns: 100px 100px;
        }
        .grid-item {
            border: 1px solid black;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>
<body>
    <div class="grid-container">
        <div class="grid-item">1</div>
        <div class="grid-item">2</div>
    </div>
</body>
</html>
```
#### Explanation:
> The display: grid property is used to create a grid layout. The grid-template-columns: 100px 100px property defines two columns each of 100px width. The divs inside the grid container no longer take up the whole line but are aligned next to each other as columns.

### 3. Adding Column and Row Gaps :
> You can adjust the gaps between the columns and rows using column-gap and row-gap properties.

#### Example:
![image](https://github.com/karthikeya03/HTML-CSS/assets/120096427/01acc283-1b45-4193-8e30-a165cc71690c)

``` css
.grid-container {
    display: grid;
    grid-template-columns: 100px 100px 100px;
    column-gap: 20px; /* 20px gap between columns */
    row-gap: 20px;    /* 20px gap between rows */
}
```

### 5. Column Gap :

> The column-gap property defines the space between the columns.
 ![image](https://github.com/karthikeya03/HTML-CSS/assets/120096427/9bd1281d-75d3-4dab-887e-d31a1c50ca07)

### 6. Row Gap :

> The row-gap property defines the space between the rows.

### 7. Grid Columns with Fractional Units :
> You can use fractional units to make the columns responsive. The 1fr unit is a flexible unit that takes up one fraction of the available space.

``` css
.grid-container {
    display: grid;
    grid-template-columns: 1fr 1fr 1fr; /* Three equal-width columns */
}
```
<br>
> Using 1fr 1fr 1fr makes three columns that equally divide the available space.

![image](https://github.com/karthikeya03/HTML-CSS/assets/120096427/f8b2a032-6e2a-4a22-b472-c5354983d85a)


### 8. Full-width Grid Items :
> Use width: 100% to make the items fit within the container.

```
.grid-item {
    width: 100%;
    border: 1px solid black;
    padding: 20px;
    text-align: center;
}
```

### 9. CSS Grid Layout for a `div` :

![image](https://github.com/karthikeya03/HTML-CSS/assets/120096427/4fb439e9-d543-4729-8c8e-4ed008add69e)


## Problem Statement:

> When using CSS Grid, a common issue is that the `div` no longer takes up the entire line, and its child elements are arranged in a grid format instead. Let's explore this with an example.

## Example:

1. **HTML Structure**:

   ```html
   <div class="grid-container">
       <div>Item 1</div>
       <div>Item 2</div>
   </div>
   ```

2. **CSS Styles**:

   ```css
   .grid-container {
       display: grid;
       grid-template-columns: 100px 100px;
   }
   ```

## Explanation:

- **Step 1**: Define a `div` with a class of `grid-container`.
- **Step 2**: Apply CSS to the `grid-container` to create a grid layout.

The key properties used here are:

- `display: grid;` - This turns the `div` into a grid container.
- `grid-template-columns: 100px 100px;` - This defines two columns, each 100px wide.

### Visual Representation:

#### Initial Structure:

> Without CSS Grid, the `div` would take up the whole line:

![Initial \`div\` layout](https://github.com/karthikeya03/HTML-CSS/assets/120096427/35ee5886-19de-490c-ace9-ad21626f2e67)

### After Applying CSS Grid:

With the grid layout applied, the `div` no longer takes up the entire line, and the child elements are arranged in a 2-column grid:

![Grid \`div\` layout](https://github.com/karthikeya03/HTML-CSS/assets/120096427/c92ffa38-5734-437a-828d-c12fda4e01a7)

## Additional Tips:

1. **Column Gaps**:
   To add space between columns, use the `grid-gap` property:

   ```css
   .grid-container {
       display: grid;
       grid-template-columns: 100px 100px;
       grid-gap: 10px;
   }
   ```

2. **Responsive Design**:
   For a responsive grid, use relative units like percentages or fractions:

   ```css
   .grid-container {
       display: grid;
       grid-template-columns: 1fr 1fr;
       grid-gap: 10px;
   }
   ```

3. **Aligning Items**:
   You can also align items within the grid:

   ```css
   .grid-container {
       display: grid;
       grid-template-columns: 100px 100px;
       align-items: center; /* Align items vertically */
       justify-items: center; /* Align items horizontally */
   }
   ```

Here are some exercises you can practice:

![image](https://github.com/karthikeya03/HTML-CSS/assets/120096427/03ba64c3-ddb2-4f97-a7f9-3e53a4517a89)
![image](https://github.com/karthikeya03/HTML-CSS/assets/120096427/93b8b0b9-888c-4b96-8aec-1314764c135c)

# Lesson 12: Flexbox

> Flexbox is another way to create layouts. It's similar to CSS Grid but more flexible.

![image](https://github.com/user-attachments/assets/9128cb32-9108-4b0f-8239-e4f131217f10)


## Definitions

- **display: flex;**: This makes the container a flex container and enables Flexbox layout.
- **flex-direction: row;**: This sets the direction of the flex items to be in a row.
- **justify-content**: Defines how the browser distributes space between and around content items along the main-axis of a flex container.

> **Justify content and align-items should be used in flex boxes**
> **Flex-direction : row : very important to keep items aligned left and right**
>  **Flex-direction : coloumn : very important to keep items aligned top and bottom**

  ![image](https://github.com/user-attachments/assets/4a92a309-c891-4031-8d8e-1529aa96ab44)

  - **center**: Centers the items in the container.
  - **space-between**: Distributes items evenly with the first item at the start and the last item at the end.
- **align-items**: Defines how the browser distributes space between and around content items along the cross-axis of their container.
  - **stretch**: Stretches the items to fill the container.
  - **start**: Aligns the items to the start of the container.
  - **end**: Aligns the items to the end of the container.
  - **center**: Centers the items in the container.
    
![image](https://github.com/user-attachments/assets/7b6e341c-198e-4a31-9eb9-1bbef73f7f64)

## Examples

```html
<div style="display: flex; justify-content: center;">
  <div style="background-color: lightblue; width: 100px;">100px</div>
  <div style="background-color: lightpink; width: 100px;">100px</div>
  <div style="background-color: lightblue; width: 100px;">100px</div>
</div>
```

![justify-content: center](https://github.com/user-attachments/assets/f9bef927-d693-49ba-9eb2-ccf968fb3d09)

```html
<div style="display: flex; justify-content: space-between;">
  <div style="background-color: lightblue; width: 100px;">100px</div>
  <div style="background-color: lightpink; width: 100px;">100px</div>
  <div style="background-color: lightblue; width: 100px;">100px</div>
</div>
```

![justify-content: space-between](https://github.com/user-attachments/assets/40cb480f-39ed-4191-8514-65f1c83b5ce0)

```html
<div style="display: flex; justify-content: space-between; align-items: stretch;">
  <div style="background-color: lightblue; width: 100px;">100px</div>
  <div style="background-color: lightpink; width: 100px;">100px</div>
  <div style="background-color: lightblue; width: 100px;">100px</div>
</div>
```

![align-items: stretch](https://github.com/user-attachments/assets/d38ce8ac-e37d-434a-b2d5-48a2aaed223e)

```html
<div style="display: flex; justify-content: space-between; align-items: start;">
  <div style="background-color: lightblue; width: 100px;">100px</div>
  <div style="background-color: lightpink; width: 100px;">100px</div>
  <div style="background-color: lightblue; width: 100px;">100px</div>
</div>
```

![align-items: start](https://github.com/user-attachments/assets/db765625-ef9c-412e-bc62-d89757bcf1af)

```html
<div style="display: flex; justify-content: space-between; align-items: center;">
  <div style="background-color: lightblue; width: 100px;">100px</div>
  <div style="background-color: lightpink; width: 100px;">100px</div>
  <div style="background-color: lightblue; width: 100px;">100px</div>
</div>
```

![align-items: center](https://github.com/user-attachments/assets/bd523fdb-bf4a-4a46-959b-22710e640f9a)

## Practical Exercise

### Create a Header with Flexbox

1. Create a `div` named `header`.
2. Create three `div` elements: `left-section`, `middle-section`, `right-section`.

```html
.header {
  height: 55px;
  display: flex;
  flex-direction: row;
}

.left-section {
  width: 200px;
}

.middle-section {
  flex: 1;
}

.right-section {
  width: 200px;
  max-width: 300px; /* The maximum width when flexed can be 300px */
}
```

![Flexbox Header](https://github.com/user-attachments/assets/190d0610-7759-493f-a7ef-eaf6186b7387)

![Flexbox Practice](https://github.com/user-attachments/assets/3429fab5-4775-44ff-9e41-6df2f495309b)

```
## Additional Code Examples

```html
<div style="display: flex; justify-content: center;">
  justify content: center;
</div>

<div style="display: flex; justify-content: space-between;">
  justify content: space-between;
</div>

<div style="display: flex; justify-content: space-between; align-items: stretch;">
  justify content: space-between;
  align-items: stretch;
  align-items: start;
  align-items: end;
  align-items: center;
</div>
```

## Additional Background Color Example

```html
<div style="background-color: lightblue; width: 100px;">100px</div>
<div style="background-color: lightpink; width: 100px;">100px</div>
<div style="background-color: lightblue; width: 100px;">100px</div>
```

![Background Color Example](https://github.com/user-attachments/assets/6f076b0d-2b6f-4b67-971b-f820219ca57e)

# Lesson 13: Nested Flexbox :

## Definitions :

- **box-shadow: inset 1px 2px 5px rgba(0,0,0, 0.15);**: This applies an inset shadow to the element.
  - **1px horizontal**: The horizontal offset of the shadow.
  - **2px to bottom**: The vertical offset of the shadow.
  - **0.15 transparency**: The transparency level of the shadow.
- **justify-content: space-between;**: Distributes items evenly with the first item at the start and the last item at the end.

### Preventing Shrinkage

- **flex-shrink: 0;**: To prevent certain items from shrinking.

```html
{
  flex-shrink: 0;
}
```

### Allowing Shrinkage

- **width: 0;**: To allow the item to shrink.

```html
{
  width: 0;
}
```

## Examples

```html
<div style="display: flex; justify-content: space-between; box-shadow: inset 1px 2px 5px rgba(0,0,0,0.15);">
  <div style="background-color: lightblue; width: 100px; flex-shrink: 0;">100px, No Shrink</div>
  <div style="background-color: lightpink; width: 0; flex: 1;">Flexible Shrink</div>
  <div style="background-color: lightblue; width: 100px;">100px, Shrink</div>
</div>
```

## Exercises

Here are some exercises you can practice:

![Nested Flexbox Exercise 1](https://github.com/user-attachments/assets/86efedfc-dfb5-4df7-9ff5-c34242c303d8)

![Nested Flexbox Exercise 2](https://github.com/user-attachments/assets/57570be1-6c60-4dca-a6ac-c7455511fb4f)

![Nested Flexbox Exercise 3](https://github.com/user-attachments/assets/484ba4f4-5fc0-4de6-844e-77ab453c717b)

# Lesson 14: CSS Positioning

## Types of Positions:

![image](https://github.com/user-attachments/assets/5a391a79-d15b-4345-a935-ea41d2add9f1)


### 1. Static

- **Definition**: This is the default position for HTML elements. When an element is positioned static, it follows the normal flow of the document, which means it is not affected by top, bottom, left, or right properties.

  ![image](https://github.com/user-attachments/assets/640a4fa1-abba-4d5b-bda0-5f97baa326c2)

- **Example**:

```html
<div style="height: 100px; width: 100px; position: static;"></div>
```

### 2. Fixed

- **Definition**: An element with a fixed position is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. It is removed from the normal document flow.
- **Properties**:
  - **top**: Specifies the distance from the top of the viewport. If set to `0px`, the element sticks to the top when scrolled.
  - **left**: Specifies the distance from the left of the viewport. If set to `50px`, the element will be 50px from the left edge of the viewport.
  - **right** and **bottom**: Similarly specify the distance from the right and bottom of the viewport respectively.
- **Padding**: Adding padding ensures that the fixed header does not cover the content of the page.
  
  ![image](https://github.com/user-attachments/assets/359c810c-2aa2-43dd-8e6c-910bc10eabfb)

- **Example**:

```html
<div style="height: 100px; width: 100px; position: fixed; top: 0px; left: 50px;"></div>
```

#### Padding

Adding padding ensures that the fixed header does not cover the content of the page.

![image](https://github.com/user-attachments/assets/876a57ee-a704-442e-91bc-5b9de91577bc)

## Exercises

### Exercise 1

- **Description**: Position a header at the top of the page with fixed positioning.
- **HTML**:

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    header {
      position: fixed;
      top: 0;
      left: 0;
      width: 100%;
      background-color: #333;
      color: white;
      padding: 10px 0;
      text-align: center;
    }
    body {
      padding-top: 50px; /* Add padding to avoid content being hidden by the fixed header */
    }
  </style>
</head>
<body>
  <header>Fixed Header</header>
  <p>Content goes here...</p>
</body>
</html>
```

### Exercise 2

- **Description**: Create a sidebar that remains fixed on the left side of the page when scrolling.
- **HTML**:

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    .sidebar {
      position: fixed;
      top: 0;
      left: 0;
      width: 200px;
      height: 100%;
      background-color: #f4f4f4;
      padding: 20px;
    }
    .content {
      margin-left: 220px; /* Add margin to avoid content being hidden by the fixed sidebar */
    }
  </style>
</head>
<body>
  <div class="sidebar">Fixed Sidebar</div>
  <div class="content">
    <p>Content goes here...</p>
  </div>
</body>
</html>
```

### Exercise 3

- **Description**: Create a footer that remains fixed at the bottom of the page.
- **HTML**:

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    .footer {
      position: fixed;
      bottom: 0;
      left: 0;
      width: 100%;
      background-color: #333;
      color: white;
      text-align: center;
      padding: 10px 0;
    }
  </style>
</head>
<body>
  <p>Content goes here...</p>
  <div class="footer">Fixed Footer</div>
</body>
</html>
```

By practicing these exercises, you can get a good understanding of how fixed positioning works and how to use it effectively in your web design projects :

![image](https://github.com/user-attachments/assets/f9199a69-dcb4-46ed-b1fe-f8bb345f5889)
<br>
![image](https://github.com/user-attachments/assets/de4f4f87-033d-422c-ba97-01a413a036ba)
<br>
![image](https://github.com/user-attachments/assets/fc8fbd9d-7ebe-40a3-bd38-2be8440a4e5e)


# Lesson 15. Position Absolute and Relative

![image](https://github.com/user-attachments/assets/7f09962f-4284-403e-b3d9-78253d555b45)


## 1. Absolute Positioning :

![image](https://github.com/user-attachments/assets/dabbc882-a8ad-4376-a4de-ee7a8e8dd20c)

When an element is positioned absolutely, it is removed from the normal document flow and positioned relative to its nearest positioned ancestor (if any); otherwise, it is placed relative to the initial containing block.

![image](https://github.com/user-attachments/assets/bd9fb972-9028-45c9-8b42-197af94d56d3)

### Position Fixed vs. Position Absolute

- **Position Fixed**: The element is positioned relative to the browser window. It does not move when the page is scrolled.

  ![image](https://github.com/user-attachments/assets/3d362578-69c2-4779-a411-1da374f8dadb)

- **Position Absolute**: The element is positioned relative to its nearest positioned ancestor. It moves with the page when scrolled.

## 2. z-index :

![image](https://github.com/user-attachments/assets/ad913141-b77b-4e18-9e11-aedad8f875eb)


The `z-index` property determines the stack order of elements. Elements with a higher `z-index` will appear in front of those with a lower `z-index`.

![image](https://github.com/user-attachments/assets/bc67005b-fa9d-4146-b6bc-28dd71639506)


- **Example**:

  ![image](https://github.com/user-attachments/assets/47431b4b-2510-4547-91c0-174bb769ab63)

  In this example, the absolutely positioned element is on the header. If the `z-index` of the header is 1 and the `z-index` of the absolute element is 0, the header will appear on top.

  ![image](https://github.com/user-attachments/assets/f4ad07fb-e7fa-4aab-93c4-05cfb4afff34)

  Changing the `z-index` of the header to 1 and keeping the default `z-index` of the absolute element to 0 will make the header appear on top.

Position absolute is particularly useful when an absolutely positioned element is inside a position fixed element. It will be placed relative to the position fixed element.

![image](https://github.com/user-attachments/assets/c7ac4cea-8a14-474c-af9a-ef00e5ef1cc7)


- **Example**:

  ![image](https://github.com/user-attachments/assets/92f15bb7-2908-4b58-8246-81afa5871212)

  In this example, the cross symbol is positioned at the corner of the sidebar to close it. The absolute position within the fixed position ensures it appears in the corner.

## 3. Relative Positioning :

![image](https://github.com/user-attachments/assets/8300f399-85fe-4793-838d-00d1efaadcae)

When an element is positioned relatively, it is positioned relative to its normal position. This means it can be moved from its original position, but it still occupies the space in the document flow.

- **Relative Positioning Example**:

  ![image](https://github.com/user-attachments/assets/1c40e4f6-7000-42fa-8842-5e8746b13d51)

  Even though the elements are fixed, using position relative allows them to move with the page.

To keep a tiny object inside a main div, the main div should have `position: relative` and the tiny object should have `position: absolute`.

# POSITION ABSOLUTE INSIDE POSITION RELATIVE

![image](https://github.com/user-attachments/assets/0f6b99df-f3ac-48e3-bd84-513edba57c78)

# Lesson 15. Position Absolute and Relative

## 1. Absolute Positioning

When an element is positioned absolutely, it is removed from the normal document flow and positioned relative to its nearest positioned ancestor (if any); otherwise, it is placed relative to the initial containing block.

![image](https://github.com/user-attachments/assets/bd9fb972-9028-45c9-8b42-197af94d56d3)

### Position Fixed vs. Position Absolute

- **Position Fixed**: The element is positioned relative to the browser window. It does not move when the page is scrolled.

  ![image](https://github.com/user-attachments/assets/3d362578-69c2-4779-a411-1da374f8dadb)

- **Position Absolute**: The element is positioned relative to its nearest positioned ancestor. It moves with the page when scrolled.

## 2. z-index

The `z-index` property determines the stack order of elements. Elements with a higher `z-index` will appear in front of those with a lower `z-index`.

- **Example**:

  ![image](https://github.com/user-attachments/assets/47431b4b-2510-4547-91c0-174bb769ab63)

  In this example, the absolutely positioned element is on the header. If the `z-index` of the header is 1 and the `z-index` of the absolute element is 0, the header will appear on top.

  ![image](https://github.com/user-attachments/assets/f4ad07fb-e7fa-4aab-93c4-05cfb4afff34)

  Changing the `z-index` of the header to 1 and keeping the default `z-index` of the absolute element to 0 will make the header appear on top.

Position absolute is particularly useful when an absolutely positioned element is inside a position fixed element. It will be placed relative to the position fixed element.

- **Example**:

  ![image](https://github.com/user-attachments/assets/92f15bb7-2908-4b58-8246-81afa5871212)

  In this example, the cross symbol is positioned at the corner of the sidebar to close it. The absolute position within the fixed position ensures it appears in the corner.

## 3. Relative Positioning

When an element is positioned relatively, it is positioned relative to its normal position. This means it can be moved from its original position, but it still occupies the space in the document flow.

- **Relative Positioning Example**:

  ![image](https://github.com/user-attachments/assets/1c40e4f6-7000-42fa-8842-5e8746b13d51)

  Even though the elements are fixed, using position relative allows them to move with the page.

To keep a tiny object inside a main div, the main div should have `position: fixed` and the tiny object should have `position: absolute`.

### Responsiveness and Media Queries

To make the website look good on every screen size, use media queries:

![image](https://github.com/user-attachments/assets/ba90a23e-ee8a-4398-a399-e3660a96912f)

#### Media Queries Examples

```css
@media (max-width: 600px) {
    /* Styles for screens with a width of 600px or less */
}

@media (min-width: 1000px) {
    /* Styles for screens with a width of 1000px or more */
}

@media (max-width: 600px) and (min-width: 1000px) {
    .container {
        grid-template-columns: 1fr 1fr 1fr;
    }
}
```

This example sets three columns when the media size is between 600px and 1000px. For less than 600px, adjust to two columns, and for more than 1000px, adjust to four columns.

![image](https://github.com/user-attachments/assets/7667289b-df45-4b71-a7e8-d221a3167714)

## Final Lesson: Some More CSS Properties

### 1. Hover

```css
.sidebar-link:hover {
    background-color: grey;
}
```

> Gives a grey background color when hovered over.

![image](https://github.com/user-attachments/assets/a6c64eab-d1a8-483c-af5e-165ac39a6402)

### 2. CSS Selectors

1. **With Comma**: Target multiple classes at the same time.
2. **With Space**: Target `<img>` elements inside elements with `class="class1"`.
3. **With a Dot**: Target an element within a specific class, not the entire page.

![image](https://github.com/user-attachments/assets/b12ad8ed-4fc4-45eb-bb02-0a0e46d7a154)
<br>
![image](https://github.com/user-attachments/assets/a600de17-f9d5-4bbb-9d9d-b465bee79996)

### 3. Tooltips

Tooltips appear when hovered over an icon. Set the opacity of the button to zero normally, and to one on hover.

![image](https://github.com/user-attachments/assets/cccc0dc0-c405-48ac-a83c-82d6fa418e31)

### 4. White Space No Wrap

![image](https://github.com/user-attachments/assets/7ad54342-8b15-4ab8-adb8-2d98774797f3)

### Exercises :

![image](https://github.com/user-attachments/assets/fcd98f5d-fba9-41ae-a080-3a07380cfa54)
![image](https://github.com/user-attachments/assets/c3153f95-9814-41d1-8aac-3906e1822e86)

### 5. Padding

Instead of using individual padding for each side:

![image](https://github.com/user-attachments/assets/317fcf6e-61f4-462f-a394-094333ccd389)

Use shorthand padding:

```css
padding: 4px;
```

This sets padding on all four sides.

![image](https://github.com/user-attachments/assets/cda955c3-d214-4738-b46e-8068e4232e97)

The order for shorthand padding is top, right, bottom, and left. Same for margin.

### 6. Inheritance

A text property set on an outer element will be passed down to inner elements.

![image](https://github.com/user-attachments/assets/5f88e216-2a6f-4fae-a632-92079e547890)

It mostly works with text properties only.

### 7. CSS Specificity

If multiple CSS selectors change the same property on the same element, CSS Specificity determines which selector "wins" (which style gets applied).

![image](https://github.com/user-attachments/assets/23c43b80-2dc5-4a62-b2f6-3e861f15c500)

### 8. CSS Specificity Rules

Here's the full set of CSS Specificity Rules:

![image](https://github.com/user-attachments/assets/320f430f-12f7-4f29-b6ab-c9b2bae0085b)

### 9. Semantic Elements

Elements that work the same way as `<div>`, but also give the HTML meaning when screen readers, search engines, or other devices read the website.

> Common semantic elements include: `<header>, <nav>, <main>, <section>, etc.`
![image](https://github.com/user-attachments/assets/6cc0ce66-d63c-45f7-b4dc-e5b63c7cf27a)
> Nav: The <nav> tag defines a set of navigation links.
> Notice that NOT all links of a document should be inside a <nav> element.
![image](https://github.com/user-attachments/assets/01262be5-9aa2-473b-85d8-fbef6b7e7e16)

### 10. Comments

![image](https://github.com/user-attachments/assets/5e36a1cf-b51a-4d6e-b2a2-2465eadd3bd1)

### Last Image

![image](https://github.com/user-attachments/assets/b329bc84-5421-46d8-89e1-6bbfd7415f88)

### Exercises :
![image](https://github.com/user-attachments/assets/be9919f0-7890-43cc-b19d-0a550058ed17)
<br>
![image](https://github.com/user-attachments/assets/c213c791-3d90-48af-8954-70050e03fa4a)
<br>
![image](https://github.com/user-attachments/assets/d99d86af-9ccd-4f52-aee7-1b4f76adf803)


