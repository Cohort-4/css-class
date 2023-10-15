for images
----------
`img{
  max-width: 100%
}`


hero container
--------------
`hero-container{
  min-height: 75vh
}`

- Remove margin-top
- then reduce on small devices

Info Container
- remove padding from .info-container

.info-container {
  padding: 20px; // remove it
}

courses
-------

hero button at small sizes
--------------------------

add max width of 100%

```css

@media (max-width: 768px) {

  .btn {
    min-width: 100%;
  }

}
```

Subscribe section
------------------

- Add a form and button for users to subscribe

Footer
--------
Fix footer responsive issue and add more content