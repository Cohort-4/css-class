CSS Module
------------
A CSS Module is a CSS file in which all class names and animation names 
are scoped locally by default. CSS Modules let you write styles in CSS 
files but consume them as JavaScript objects for additional processing and safety.
CSS Modules are very popular because they automatically make class and animation names 
unique so you don’t have to worry about selector name collisions.


CSS Modules create unique class names for each component, so you don't have to worry about style collisions.

`import styles from "page.module.css"`

```css
    .container{
      padding: 2rem;
      background-color: purple;
    }
```

```html
    <div className={styles.container}>
      <h1>Hello CSS Module</h1>
      <p>
        class names and animation names are scoped locally by default.
      </p>
    </div>
```


Credit/ Reference
-----------------

[how to style with css-modules](https://www.gatsbyjs.com/docs/how-to/styling/css-modules/#:~:text=A%20CSS%20Module%20is%20a,for%20additional%20processing%20and%20safety.)

[https://www.gatsbyjs.com/docs/tutorial/getting-started/part-2/#css-modules](https://www.gatsbyjs.com/docs/tutorial/getting-started/part-2/#css-modules)