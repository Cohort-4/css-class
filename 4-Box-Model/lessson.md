The CSS Box Model
------------------

The CSS box model is essentially a box that wraps around every HTML element. It consists of: margins, borders, padding, and the actual content. The image below illustrates the box model:

![https://web-dev.imgix.net/image/VbAJIREinuYvovrBzzvEyZOpw5w1/ECuEOJEGnudhXW5JEFih.svg](https://web-dev.imgix.net/image/VbAJIREinuYvovrBzzvEyZOpw5w1/ECuEOJEGnudhXW5JEFih.svg)

Calculating Total element width
--------------------------------

`Total element width = width + left padding + right padding + left border + right border + left margin + right margin`


Calculating Total element height
---------------------------------

`Total element height = height + top padding + bottom padding + top border + bottom border + top margin + bottom margin`


illustration

This `<div>` element will have a total width of ---px:

```css 

div {
    width: 320px;
    padding: 10px;
    border: 5px solid gray;
    margin: 0;
}
```
How wide do you think .my-box will be?

```css

  .my-box {
    width: 200px;
    border: 10px solid;
    padding: 20px;
}

```

Credit / Reference

[https://web.dev/learn/css/box-model/](https://web.dev/learn/css/box-model/)

[https://www.w3schools.com/css/css_boxmodel.asp](https://www.w3schools.com/css/css_boxmodel.asp)

[Introduction to the CSS box model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model/Introduction_to_the_CSS_box_model)