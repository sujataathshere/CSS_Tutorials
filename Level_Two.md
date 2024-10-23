## Box Model in CSS
1. Height
- By default, it sets the content area height of the element
```css
div {
    height:50px;
}
```
2. Width
- By default, it sets the content area width of the element
```css
div {
    width:50px;
}
```
3. Border
- Used to set an element's border
- Used to round the corners of an element's outer border edge
```css
    border-style: solid/dashed/dotted/double;
    border-width: 2px;
    border-color: brown;
    /* Shorthand Border:width style color */
    border:2px solid brown;
    border-radius:10px;
    border-radius:50%;
```
4. Padding
-
```css
    padding-left:25px;
    padding-right:25px;
    padding-top:25px;
    padding-bottom:25px;
    /* From each direction */
    padding:20px;
    /* Shorthand p:top right bottom left -> clockwise */
    padding:1px 2px 3px 4px;
```
5. Margin
- 
```css
    margin-left:25px;
    margin-right:25px;
    margin-top:25px;
    margin-bottom:25px;
    /* From each direction */
    margin:20px;
    /* Shorthand p:top right bottom left -> clockwise */
    margin:1px 2px 3px 4px;
```