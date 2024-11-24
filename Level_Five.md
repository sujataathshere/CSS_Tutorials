- Learned transition / transform / animation
- rotate in 2d / 3d space
- change size / effects

## Transitions
- Transitions enables you to define the transition between two states of an element.
- While going to from 1 state to another state we apply some transition to show how changes happens/convert a state
1. transition-property
- property you want to transition (font-size, width, etc.)
```css
div{
    transition-property: all;
    /* Apply on all the transition property */
}
```
2. transition-duration
- 2s / 4ms..
```css
div{
    transition-duration: 2s;
}
```
3. transition-timing-function
- ease-in / ease-out / linear / steps..
```css
div{
    transition-timing-function:steps(3);
}
```
4. transition-delay
- 2s / 4ms..
- Defines when the transition will start. It allows a transition to begin execution some period of time from when it is applied.
```css
div{
    transition-delay:1s;
}
```
## Transition Shorthand
- property name | duration | timing-function | delay
```css
div{
    transition : font-size 2s ease-in-out 0.2s;
}
```
## Pseudo Classes
- It is used to define different states.
- Eg. hover, active, focus, visited, etc.
1. Hover
- It is used to add special effects to an element when the mouse pointer hovers over it.
- This is commonly used for buttons and links to enhance interactivity.
```css
div:hover{
    background-color: lightgreen;
    color: white;
    font-size: 20px;
}
```
2. Active
- It applies to an element that is currently being activated by the user, such as when a button is clicked.
```css
div:active{
    background-color: darkolivegreen;
}
```
## CSS Transform
- Used to apply 2D & 3D transformations to an element
1. Rotate
- rotate, rotateX, rotateY, rotateZ.
```css
div{
    transform:rotate(45deg);
    /* OR */
    rotate:45deg;
}
```
2. Scale
- scale, scaleX, scaleY. 
```css
div{
    transform:scale(2);
    /* It will change according both x/y axis */

    transform:scale(1, 2);
    /* Value should be same along x-axis bt 
       Value should be change/double along y-axis
    */
}
```
3. Translate
- translate, translateX, translateY.
```css
div{
    transform:translate(20px);
    /*  */
    transform:translate(20px, 50px);
    /* Move along with x axis with 20px and y axis with 50px*/
    transform:translateX(20px);
    transform:translateY(20px);
    /* Move along with x And y axis */
}
```
4. Skew
- It is mixture of different effects. 
```css
div{
    transform:skew(45deg);
    /* From 2 corners streching by 45 degree */
    transform:skewX(45deg);
    /* From 2 corners streching by 45 degree */
    transform:skewY(45deg);
    /* From 2 corners streching by 45 degree */
}
```
## Animation
- To animate CSS elements
- This is a animation template
```css
@keyframe myName {
    from{font-size:20px;}
    to{font-size:40px;}
}
```
## Animation Properties
- To apply animation we used animation properties
1. animation-name
- Ued to give animation name
```css
div{
    animation-name:colorAnimate;
}
```
2. animation-duration
- Used to show animation time duration
```css
div{
    animation-duration: 3s;
}
```
3. animation-timing-function
- Used to show slow/fast/in-steps animation
```css
div{
    animation-timing-function: ease-in;
}
```
4. animation-delay
- After how much time animation should display
```css
div{
    animation-delay: 1s;
}
```
5. animation-iteration-count
- How many times should my animation apply
- 1/2/3.../infinite
```css
div{
    animation-iteration-count: 5 ;
}
```
6. animation-direction
- normal/reverse/alternate/alternate-reverse
```css
div{
    /* Single Animation */
    animation-direction: normal;
    /* Multiple Animation */
    animation-direction: normal, reverse;
    /* Global values */
    animation-direction: inherit;
}
```