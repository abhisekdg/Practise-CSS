# Practise-CSS
https://www.udemy.com/design-and-develop-a-killer-website-with-html5-and-css3/

### FLEX PROPERTIES

```css
display: flex | inline-flex;
flex-direction: row | column
flex-wrap: wrap | nowrap | wrapreverse
flex-basis: <length>
flex-grow: <number>
flex-shrink: <number>
flex: <number>
order: <number>		
justify-content: flex-start | flex-end | center
align-self: flex-start | flex-end | center
align-items : flex-start | flex-end | center
align-content : flex-start | flex-end | center
```

```css
@media(min-width:768px) {
  container-1{
    display : flex;
  }
  container-1{
    justify-content: space-between;
  }
}
```
https://rawcdn.githack.com/abhisekdg/Practise-CSS/master/flex/flex_sample.html

```css
p:before {
    content: "";
    display: block;
    background: url("block_icon.png") no-repeat;
    width: 20px;
    height: 20px;
    float: left;
    margin: 0 6px 0 0;
}
```
```Input : <p>paragraph text</p>```
Result : <img src="https://rawcdn.githack.com/abhisekdg/Practise-CSS/master/images/block_icon.png" width="20"> paragraph text

## Clearing floats 

http://krasimirtsonev.com/blog/article/CSS-before-and-after-pseudo-elements-in-practice

```html
<a href="#">Home</a>
<a href="#">Products</a>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
```

```css
p:before {
    content: "";
    display: block;
    clear: both;
}
```

<a href="#">Home</a>
<a href="#">Products</a>
<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>

## CSS Properties

```css
position: relative;
box-sizing: border-box;
overflow: hidden;
transform: translateY(-0px);
background-repeat: no-repeat;
background-position: 50%;
background-size: contain;
display: contents | inline-block;
vertical-align: middle;
stroke-dasharray: 1,200;
stroke-dashoffset: 0;
animation: _1KP0Jq 1.5s ease-in-out infinite;
stroke-linecap: round;
```

