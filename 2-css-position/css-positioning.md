### CSS POSITIONING
The position property specifies the type of positioning method used for an element.
There are five different position values:
- static
- relative
- fixed
- absolute
- sticky

Elements are then positioned using the top, bottom, left, and right properties. However, these properties will not work unless the position property is set first. They also work differently depending on the position value.


position: static
-----------------
HTML elements are positioned static by default.
Static positioned elements are not affected by the top, bottom, left, and right properties.
An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:

position: relative
-------------------
An element with position: relative; is positioned relative to its normal position.
Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.

position: fixed
-------------------
An element with position: fixed; is positioned relative to the viewport, which means it always stays in the same place even if the page is scrolled. The top, right, bottom, and left properties are used to position the element.
A fixed element does not leave a gap in the page where it would normally have been located.

position: absolute
-------------------
An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.Absolute positioned elements are removed from the normal flow, and can overlap elements.


position: sticky
--------------------
An element with position: sticky; is positioned based on the user's scroll position. A sticky element toggles between relative and fixed, depending on the scroll position. It is positioned relative until a given offset position is met in the viewport - then it "sticks" in place (like position:fixed).
In this example, the sticky element sticks to the top of the page (top: 0), when you reach its scroll position.


Sample code illustration

Check `index.html` and `style.css` inside css-position folder for illustration

```css

/* RESET */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
/* position: relative */
.relative {
  border: 3px solid orange;
  padding: 0.4rem;
  position: relative;
  left: 30px;
  margin-right: 2rem;
}
/* position: relative */

/* position: absolute */
.aboslute-parent {
  border: 3px solid rebeccapurple;
  width: 400px;
  height: 250px;
  padding: 2rem;
  margin: 1rem;
  position: relative;
}
.absolute {
  border: 3px solid red;
  width: 150px;
  padding: 0.4rem;
  position: absolute;
  bottom: 10px;
  right: 10px;
}
/* position: absolute */

/* position sticky */
.sticky {
  border: 1px solid rgb(255, 0, 162);
  background-color: green;
  color: white;
  padding: 1rem;
  position: sticky;
  top: 0px;
}
/* position sticky */

/* position: fixed */
.fixed {
  border: 3px solid purple;
  padding: 1rem;
  position: fixed;
  bottom: 0px;
  right: 0px;
  background-color: orange;
  cursor: pointer;
  margin: 1rem;
}
/* position: fixed */

```