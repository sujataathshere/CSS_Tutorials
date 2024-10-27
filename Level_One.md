## CSS
- Cascading Style Sheet
- It is a language that is used to describe the style of a document(HTML).

## Inline Style
- Styling inside element
- `<h1 styel="color:red">Apna College</h1>`

## Internal CSS
- Styling inside `<style>` tag, which is written in a head tag
```html
<style>
    h4{
        color: red;
    }
</style>
```
## External CSS
- Styling inside css file
```css
h4{
    color: red;
}
```
## Color Property
- Used to set the color of foreground(front side)
- Eg. color: red;
- We can set propety on Text, Button element, link

## Background Color Property
- Used to set the color of background
- Eg. background-color:black;

## Color System
- Using "color picker" we can set the color
- Color Palette

1. RGB -> 0-255
- Eg. rgb(255,255,255)

2. HEX -> #00-#ff
- Eg. #22bfb2

3. HSL -> %
- Eg. 175',70%,44%

## Selectors
1. Universal Selector `*{}`
- Set everything through the asterik
- Eg. Text color, Font, etc.
```css
* {
    color: blue;
}
```
2. Element Selector `h1{}`
- Apply color on element
- Eg. headings, paragraphs
```css
p {
    color: green;
}
```
3. Id Selector `#myId{}`
- Used to apply style on a single element
- Use Id for single element only
- Eg. `<h4 id="headingOne">This is heading1</h4>`
```css
#headingOne{
    color:greenyellow;
}
```
4. Class Selector `.myClass{}`
- Used to apply style on a multiple element
- Use class for multiple element
- Eg. `<h4 class="myClass">This is heading1</h4>`
```css
.myClass{
    color:greenyellow;
}
```
## Text Properties
1. text-align : left, center, right.
2. text-decoration : underline, overline, line-through, none, wavy, dotted.
3. font-weight : normal/bold/bolder/lighter OR 100-900
- Normal/lighter:100, Bold:600, Bolder:900
4. font-family
- 5 Generic font families : Serif, Sans-serif, Cursive, Fantasy, Monospace
5. font-size : Absolute Unit & Relative Unit
- Absolute Unit measure in pixels(px), km, cm, mm.
- Nomal size of text : 16px
- Relative Unit
6. line-height
7. text-transform : uppercase, lowercase, capitalize, none.