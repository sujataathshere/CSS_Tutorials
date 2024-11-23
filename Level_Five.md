- Lerned transition / transform / animation
- rotate in 2d / 3d space
- change size / effects

## Transitions
- Transitions enables you to define the transition between two states of an element.
- While going to from 1 state to another state we apply some transition
1. transition-property
- property you want to transition (font-size, width, etc.)
2. transition-duration
- 2s / 4ms..
3. transition-timing-function
- ease-in / ease-out / linear / steps..
4. transition-delay
- 2s / 4ms..

## Pseudo Class
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