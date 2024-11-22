* It helps in css styling & element arrangement

## Flexbox (Flexible Box Layout)
- It is a one-dimensional layout method for arranging items in rows or columns.

## Flexbox Direction (For Flex Container)
- It sets how flex items are placed in the flex container, along which axis & direction.
- flex-direction property used for container not for items.
- 
```css
flex-direction:row; (default Left To Right)
flex-direction:row-reverse; (Right To Left)
flex-direction:column; (Top To Bottom)
flex-direction:column-reverse; (Bottom To Top)
```
## Flex Properties (For Flex Container)
1. justify-content : alignment along the main axis.
- flex-start / flex-end / centre / space-evenly /
2. flex-wrap : nowrap / wrap / wrap-reverse
3. align-items : alignment along the cross axis.
4. align-content : alignment of space between & around the content along cross-axis

## Flex Properties (for Flex Item)
1. align-self : alignment of individual along the cross axis
2. flex-grow : how much a flex item will grow relative to the rest of the flex items if space is available
3. flex-shrink : how much a flex item will shrink relative to the rest of the space is available