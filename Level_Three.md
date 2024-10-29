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
## Position Property : static / relative / absolute / fixed
- This position CSS property sets how an element is positioned in a document.
1. Static : top / right / bottom / left / z-index
- default position (The top, tight, bottom, left, & z-index properties have no effect)

* z-index
- It decides the stack level of elements
- Overlapping elements with a larger z-index cover those with a smaller one.

2. Relative
- Element is relative to itself. (The top, right, bottom, left, & z-index will work)

3. Absolute
- Positioned relative to its closest positioned(non-static) ancestor. (removed from the flow)

4. Fixed
- Positioned relative to browser. (removed from flow)

5. Sticky
- Positioned based on user's scroll position