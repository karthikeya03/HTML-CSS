# Learning HTML

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

## 2. CSS Basics :

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

## 3. Hovers, Transitions, and Shadows :

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

## 4. Chrome DevTools & CSS Box Model :

### 1. Dev tools :

> What are the dev tools? :
> . open the inspect button to look at the developer tools of any website of your choice
> . click on the cursor button on the left most to find different elements adn their css, HTML

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

In CSS, the box model is essential for designing and laying out web pages. The following diagram illustrates the relationships between margins, borders, padding, and content:

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

### 2. vertical align : top

> aligns everything to the top

### Exercises You Can Practice DevTools & CSS Box Models on :

![CSS BOX MODEL](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/1.1.png) <br>
![CSS BOX MODEL](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/1.png)

## 5. How to style text :

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

Output : `The text will be red `

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

# Lession 6. The Html structure :

![width](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/h.1.png)
<! DOCTYPE HTML>
not an element ts just a sepcal lne that has adds meanng to the browser
next : create a html element
HTML>
/html>
nsde html there s : body lement
HTML>
body>
/body>
/html>
every html has one html dont body elements only

body : contans all the elements that are vsble

![body](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/h.1.png)

only element that s not vsble s the ttle element
ttle > Frst website /ttle>

what ever s not vsble goes to the head element le style> and title>

rel :
rel = " stylesheet"
t tells the html waht type of file we are linking

href : what file you're going to
href =" css.css"

![body](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/h.2.png)

how to ln css to the html file :

1. create a css fle name t (.css)
2. create a html file (.html)
3. In the head add link tag and rel (relation) then href (what file we are going to

   `<link rel = "stylesheet" href =" css.css" >`

   here s the mage :
   ![body](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/h.3.png)
   void elements : elements that dont need a closng tag
   ex : link area base meta param source trac br

put a font in head section in your html to add the font to the website :

here is the image :
![font](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/h.11.png)

here are some excerices you can practice :
![font](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/h.12.png)


