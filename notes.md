# Learning HTML

## Introduction

To create and view websites, you need:

1. A **Web Browser**: Allows you to view and interact with your website.
2. A **Code Editor**: Helps you write the code for your website.

## HTML: HyperText Markup Language

HTML is the standard language used to create websites. It consists of a series of elements that define the structure and content of web pages.

## HTML Basics

### File Naming

- **Save As**: filename.html

### Syntax

- **Syntax**: The rules of writing code.
- **Grammar**: The structure and order of elements in HTML.

### HTML Elements

#### Button

```html
<button> Hello </button>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image1.png)

#### Paragraph

```html
<p> This is a paragraph of text. </p>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image2.png)

#### Link to Another Website

```html
<a href="https://www.youtube.com"> Link to YouTube </a>
```

- **<a>**: Anchor element used to create links.
- **href**: Attribute specifying the URL of the linked page.
- **target**: Attribute specifying where to open the linked document.

```html
<a href="https://www.youtube.com" target="_blank"> Link to YouTube </a>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image3.png)

### Extra Spaces and New Lines

Extra spaces and new lines in HTML are generally ignored.

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image4.jpeg)

### Indentation

Indentation helps keep your code readable. Use the `tab` key to indent your code.

TASKS THAT YOU CAN PRACTICE : 

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image5.png)
![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image6.png)

## CSS Basics

**Cascading Style Sheets (CSS)**: Used to change the appearance of HTML elements.

### Applying CSS to Buttons

```html
<button> SUBSCRIBE </button>
```

#### CSS

```css
<style>
button {
  background-color: red;
}
</style>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image7.png)

### CSS Selectors

Selectors are used to target HTML elements for styling.

#### Example

```css
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

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image8.png)

#### RGB Colors

Colors can be defined using RGB (Red, Green, Blue) values.

```css
background-color: rgb(255, 0, 0);
```

### Border Radius and Cursor

- **border-radius**: Defines the roundness of the corners.
- **cursor**: Defines the type of cursor to be displayed.

### Creating a Join Button

```html
<button> JOIN </button>
```

```html
<button class="subscribe-button"> SUBSCRIBE </button>
```

```css
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

### Margins

- **margin-right**: Adds space to the right of an element.

```css
margin-right: 8px;
```

#### Example

```css
.tweet-button {
  background-color: lightblue;
  color: white;
  border: none;
  border-color: blue;
  border-width: 1px;
  height: 36px;
  width: 100px;
  border-radius: 2px;
  font-weight: bold;
  font-size: 15px;
  cursor: pointer;
}
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image9.png)
![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image10.png)


## Hovers, Transitions, and Shadows

### Hover

A pseudo-class used to define the style of an element when the mouse is over it.

```css
.subscribe-button:hover {
  background-color: white;
}
```

### Active

Defines the style of an element when it is being clicked.

```css
.subscribe-button:active {
  background-color: blue;
}
```

### Opacity

Defines the transparency of an element.

```css
.subscribe-button:active {
  opacity: 0.3;
}
```

### Transitions

Defines the transition effect for properties.

```css
transition: opacity 1s;
```

#### Example

```css
.join-button:hover {
  background-color: blue;
  color: white;
}
.join-button:active {
  opacity: 0.7;
}
```








```
transition : opacity 1s;
transition : background-color : 1s;
transition : color 1s; // changes the color transition smoothly 
```

always put transition in base css : lke n .jon-button :

where ever i added image use this format 

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image1.png) change the numbers, if i add image 1 , then make it image 1, if 2 then make 2 like that.
















