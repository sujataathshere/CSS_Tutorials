## Websites
- unsplash.com -> 

## Units in CSS
1. Absolute
2. Relative (%, em, rem)
    1. Percentage(%)
    - It is often used to define a size as relative to an element's parent object.
    ```css
        width : 33%;
        margin-left : 50%;
    ```
    2. Em
    - Font size of the parent, in the case of typographical properties like font-size, & font size of the element itself, in the case of other properties like width.
    ```css
    #parent_box {
        font-size: 10px;
    }
    #child_box {
        font-size: 2em; /*2 times of parent font size : 10*2 = 20px*/
        width: 5em; /*5 times of own(child) font-size : 5*2 = 100px*/
    }
    ```
    3. Rem(Root Em)
    - Font size of the root element
    ```css
    #box {
        font-size: 2em; /*2 times of parent font size : 10*2 = 20px*/
        width: 5rem; /*5 times of body(default size) font-size : 5*16 = 80px*/
    }
    ```
    4. vh
    - Relative to 1% viewport(browser) height
    ```css
    #box {
    height: 40vh;/*40% of height of Screen size*/
    }
    ```
    5. vw
    - Relative to 1% viewport(browser) width
    ```css
    #box {
    width: 30vw;/*30% of width of Screen size*/
    }
    ```
## Position Property : static | relative | absolute | fixed
- This position CSS property sets how an element is positioned in a document.
- Main position : static / relative / absolute / fixed

1. Static
- default position (The top, tight, bottom, left, & z-index properties have no effect)
- top / right / bottom / left properties not working in static

2. Relative
- Element is relative to itself. (The top, right, bottom, left, & z-index will work)

3. Absolute
- Positioned relative to its closest positioned(non-static) ancestor. (removed from the flow)
```css
div{
    position: absolute;
    top: 10px;
    left: 500px;
}
```
4. Fixed
- Positioned relative to browser. (removed from flow)

5. Sticky
- Positioned based on user's scroll position

## z-index
- It decides the stack level of elements
- Overlapping elements with a larger z-index cover those with a smaller one.
- By default z-index is zero
```css
z-index: auto(0) /*It depends on position/How u wrote in code*/
z-index: 1/2/3... /*Used for Over*/
z-index: -1/-2/-3... /*Used for Under*/
```

## Background Image
- Used to set an image as background
- unsplash.com
```css
background-image:url("image.jpeg");
```

## Background Size : cover | contain | auto
1. Cover
- Completely fit the picture / no spaces available
- Image gets enlarge bt not repeated
- Image may not display completely bt no spaces will be available on selected area
```css
background-size:cover;
```
2. Contain
- Cover whole area & display whole image also.
- Image will be repeated on remaining space
```css
background-size:Contain;
background-repeat:no-repeat;
```