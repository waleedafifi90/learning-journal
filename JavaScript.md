# JavaScript & jQuery

**How do HTML, CSS and Javascript fit together**

* HTML is the content layer and it's file extension .html
* CSS is the presentation layer .css
* Javascript is the behavior layer .js

_HTML_
```
<!DOCTYPE html>
<html>
    <head>
        <title>Constructive &amp; Co.</ title>
        <link rel ="stylesheet" href="css/ cOl.css" />
    </ head>
    <body>
        <hl>Constructive &amp; Co.</hl>
        <script src="js/ add-content.js"></ script>
        <p>For all orders and inquiries please call
        <em>SSS-3344</ em></ p> 
    </ body>
</html>
```


_JavaScript_
```
var today= new Date();
var hourNow = today.getHours(); var greeting;
if (hourNow > 18) {
    greeting= 'Good evening!';
else if (hourNow > 12) { greeting = ' Good afternoon!' };
else if (hourNow > 0) { greeting = 'Good morni ng!' };
else {
    greeting = 'Welcome! ' ;
}
document.write( '<h3>' + greeting + '</ h3>');
```

**How to use Objects & Methods**
```
document.write('Good afternoon!');
```



## Summary
1. It is best to keep JavaScript code in its own JavaScript file
2. The HTML script element is used in HTML pages to tell the browser to load the javascropt
3. If you view the source code of the page in the browser