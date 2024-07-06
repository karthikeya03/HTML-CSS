# Learning HTML

## Introduction
> To create and view websites, you need:

1. A **Web Browser**: Allows you to view and interact with your website.
2. A **Code Editor**: Helps you write the code for your website.

## HTML: HyperText Markup Language
> HTML is the standard language used to create websites. It consists of a series of elements that define the structure and content of web pages.

## 1. HTML Basics

### 1. File Naming

- **Save As**: filename.html

### 2. Syntax

- **Syntax**: The rules of writing code.
- **Grammar**: The structure and order of elements in HTML.

### 3. HTML Elements

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/mg01.png) 

#### 4. Button

```
<button> Hello </button>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image1.png)

#### 5. Paragraph

```
<p> This is a paragraph of text. </p>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image2.png)

#### 6. Link to Another Website

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

### 7. Extra Spaces and New Lines
> Extra spaces and new lines in HTML are generally ignored.

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image4.jpeg)

### 8. Indentation
> Indentation helps keep your code readable. Use the `tab` key to indent your code.


### Exercises You Can Practice on HTML :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image5.png)
![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image6.png)

## 2. CSS Basics

**Cascading Style Sheets (CSS)**: Used to change the appearance of HTML elements.

### 1. Applying CSS to Buttons

```
<button> SUBSCRIBE </button>
```
![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/mg2.png)

#### 2. CSS

```
<style>
button {
  background-color: red;
}
</style>
```

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image7.png)

### 3. CSS Selectors
> Selectors are used to target HTML elements for styling.

#### Example

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

### 4. RGB Colors
> Colors can be defined using RGB (Red, Green, Blue) values.

```
background-color: rgb(255, 0, 0);
```

### 5. Border Radius and Cursor

- **border-radius**: Defines the roundness of the corners.
- **cursor**: Defines the type of cursor to be displayed.

  ![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image8.png)

### 6. Creating a Join Button

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

### 7. Margins

- **margin-right**: Adds space to the right of an element.

```
margin-right: 8px;
```

### Exercises You Can Practice on CSS  :
![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image9.png)
![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image10.png)

## 3. Hovers, Transitions, and Shadows

### 1. Hover
> A pseudo-class used to define the style of an element when the mouse is over it.

```
.subscribe-button:hover {
  background-color: white;
}
```

### 2. Active
> Defines the style of an element when it is being clicked.

```
.subscribe-button:active {
  background-color: blue;
}
```

### 3. Opacity
> Defines the transparency of an element.

```
.subscribe-button:active {
  opacity: 0.3;
}
```

### 4. Transitions
> Defines the transition effect for properties.

```
transition: opacity 1s;
```

#### Example

```
.join-button:hover {
  background-color: blue;
  color: white;
}
.join-button:active {
  opacity: 0.7;
}
```
### 5. Shadows
> In CSS, shadows can enhance the design by adding depth and dimension to elements. The box-shadow property is used to apply shadows to elements such as buttons or divs.

#### Example
```
.tweet-button {
  box-shadow: 0 0 0 black; /* Takes 4 values */
}
```
> Representatives : 
The box-shadow property takes the following values:

`Horizontal position: Determines the horizontal offset of the shadow.`
`Vertical position: Determines the vertical offset of the shadow.`
`Blur: Specifies the blur radius of the shadow.`
`Color: Defines the color of the shadow.`

> For instance, if you use  `10px 10px 10px black`, the shadow will be positioned `10 pixel`s to the `right`, `10 pixels down from the element`, and have a `blur radius` of `10 pixels`.

Here's an illustration:

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/MG3.png)

### 6. RGBA Value :
> The rgba value in CSS is used to define colors with transparency. It is an extension of the RGB color model, where a stands for alpha and represents the opacity level.

#### Example

```
box-shadow: 10px 10px 10px rgba(0, 0, 0, 0.6);
```

> This code will create a shadow that is 10 pixels to the right, 10 pixels down, with a blur radius of 10 pixels, and the color will be black with 60% opacity.

Here's an illustration:

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/mg4.png)

### Exercises You Can Practice on Hovers, Transitions, and Shadows :

![](https://raw.github.com/karthikeya03/HTML-CSS/JustMain/image.png)
















