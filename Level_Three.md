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