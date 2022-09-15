## inline 
Compared to display: inline, the major difference is that display: inline-block allows to set a width and height on the element.

Also, with display: inline-block, the top and bottom margins/paddings are respected, but with display: inline they are not.

Compared to display: block, the major difference is that display: inline-block does not add a line-break after the element, so the element can sit next to other elements.

## background-size: cover
Resize the background image to cover the entire container, even if it has to stretch the image or cut a little bit off one of the edges


## transform
The transform property applies a 2D or 3D transformation to an element. This property allows you to rotate, scale, move, skew, etc., elements.

### transform-translate
The translate() method moves an element from its current position (according to the parameters given for the X-axis and the Y-axis).

- Example
    ```
    div {
    transform: translate(50px, 100px);
    }
    ```

## position
The position property specifies the type of positioning method used for an element (static, relative, fixed, absolute or sticky).   
There are five different position values:

- static
- relative
- fixed
- absolute
- sticky

### position-static
HTML elements are positioned static by default.

Static positioned elements are not affected by the top, bottom, left, and right properties.

An element with position: static; is not positioned in any special way; it is always positioned according to the normal flow of the page:

This ```<div>``` element has position: static;
Here is the CSS that is used:
```
div.static {
  position: static;
  border: 3px solid #73AD21;
}
```

## position-relative
An element with position: relative; is positioned relative to its normal position.

Setting the top, right, bottom, and left properties of a relatively-positioned element will cause it to be adjusted away from its normal position. Other content will not be adjusted to fit into any gap left by the element.

This ```<div>``` element has position: relative;
Here is the CSS that is used:
```
div.relative {
  position: relative;
  left: 30px;
  border: 3px solid #73AD21;
}
```

## position-absolute
position: absolute;
An element with position: absolute; is positioned relative to the nearest positioned ancestor (instead of positioned relative to the viewport, like fixed).

However; if an absolute positioned element has no positioned ancestors, it uses the document body, and moves along with page scrolling.

Note: Absolute positioned elements are removed from the normal flow, and can overlap elements.

Here is a simple example:
```
div.absolute {
  position: absolute;
  top: 80px;
  right: 0;
  width: 200px;
  height: 100px;
  border: 3px solid #73AD21;
}
```

