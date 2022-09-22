# above-and-beyond Embedded iframe and Absolute positioning
Embedded iframe and Absolute positioning for Above and Beyond

## Attributions
- Embedded iframe --- https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe
- Absolute positioning --- https://www.w3schools.com/css/css_positioning.asp
- Responsive iframe with absolute positioning --- https://blog.duda.co/responsive-google-maps-for-your-website
```
.map-responsive{
    overflow:hidden;
    padding-bottom:56.25%;
    position:relative;
    height:0;
}

.map-responsive iframe{
    left:0;
    top:0;
    height:100%;
    width:100%;
    position:absolute;
}
``` 