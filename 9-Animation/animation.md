[CSS-Animation](https://cssfx.netlify.app/)

## CSS Animations
------------------
An animation provides the ability of element to change from one style to another. Animation is one of the ways of adding interactivity to an HTML element. 

### Animation Properties
-------------------------

The following are the some of the animation properties
- animation
- @keyframes
- animation-name
- animation-duration
- animation-delay
- animation-iteration-count
- animation-direction
- animation-timing-function
- animation-fill-mode

Illustration

- `animation` 
-------------
This is a short hand for all animation properties
```css
.identifier{
  animation: name duration timing-function delay iteration-count direction fill-mode;
}
```

- `keyframes`
---------------
This are mechanism used for assigning animation states. That is managing the timestamps states along a duration or timeline.

```css
  @keyframes keyframes-name{
    from
      { keyframes rule},
    to 
      { keyframes rule}
}
```


- The `animation-name` property: (The keyframes-name) 
------------------------------------------------------
This is a custom identifier, which allows you to provide your own name. It is a case-sensitive.

- The `animation-duration` property 
-----------------------------------
This defines the time taken (how long) for an animation to complete. Without animation-duration property, no animation will occur, because the default value is 0s (0 seconds). 

  - The `animation-delay` property
-------------------------------- 
This is a delay time for an animation to start.

- The `animation-iteration-count` property
-------------------------------------------- 
The number of times an animation should occur.

- The `animation-direction` property
--------------------------------------
 This property specifies the direction to which an animation should followed. It can be forwards, backwards or in alternate cycles. The following are the available values for `animation-direction`

    - normal: (forwards) --> This is default
    - reverse:  (backwards)
    - alternate: forwards first, then backwards
    - alternate-reverse: backwards first, then forwards

- The `animation-timing-function` property
-------------------------------------------
The speed curve of the animation. The following are the values of `animation-timing-function`:

  - ease: a slow start, then fast, then end slowly (this is default)
  - linear: same speed from start to end
  - ease-in: a slow start
  - ease-out: a slow end
  - ease-in-out: a slow start and end
  - cubic-bezier(n,n,n,n): customise your own values in a cubic-bezier function.



- The animation-fill-mode property
-----------------------------------  
 Give a style for the target element when the animation is not present (before it starts, after it ends, or both).

The animation-fill-mode property can have the following values:

  - none: Default value.
  - forwards: retain the style values that is set by the last keyframe 
  - backwards 
  - both