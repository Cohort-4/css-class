<!-- ICONS -->

### Adding Icons and Fonts to an HTML Element

- Icons: fontawesome cdn link for Icons
----------------------------------------

[https://cdnjs.com/libraries/font-awesome](https://cdnjs.com/libraries/font-awesome)

   1. Visit the link above to copy the `url` for icons
   2. Paste it in the `head` tag as shown below
   3. Then calling each icon class on an `HTML` Element.

illustration

```html
<head>
   <link
      rel="stylesheet"
      href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css"
    />
</head>
```

```html
<body>
   <a href="www.linkedin.com" class="fab fa-linkedin">linkedIn</a>
</body>
```

<!-- Google font -->

- Fonts: Adding fonts to HTML Elements from google
--------------------------------------------------

[https://fonts.google.com/](https://fonts.google.com/)

`index.html`

```html
<head>
   <link
      href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=Roboto:wght@100;300;400;500;700;900&family=Space+Grotesk:wght@600&display=swap"
      rel="stylesheet"
    />
    <link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;700&family=Poppins:wght@100;200;300;400;500;600&family=Roboto:wght@100;300;400;500;700;900&family=Space+Grotesk:wght@600&display=swap" rel="stylesheet">
</head>
```

`style.css`

```css
   body{
     font-family: 'Space Grotesk', sans-serif;
     font-family: "Poppins";
   }
  
```
