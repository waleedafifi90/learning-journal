![CSS](https://colorlib.com/wp/wp-content/uploads/sites/2/creative-css3-tutorials.jpg)
# CSS

_into_

In this section, we will look at how to make your web pages more attractive, controlling the design of them using CSS.

**Content table**

1. Introduce you to how CSS works
2. Teach you how to write CSS rules
3. Show you how CSS rules apply to HTML pages


**What is CSS?**

CSS allows you to create rules that specify how the content of an element should appear. For example, you can specify that the background of the page is cream, all paragraphs should appear in gray using the Arial typeface, or that all level one headings should be in a blue, italic, Times typeface.

**Why CSS?**
CSS allows you to create rules that control the way that each individual box (and the contents of that box) is presented.


CSS works by associating rules with HTML elements. These rules govern how the content of specified elements should be displayed. A CSS rule contains two parts: a selector and a declaration.

```
p {
    font-family: Arial;
}
```

![CSS Rule](https://mdn.mozillademos.org/files/9461/css-declaration-small.png)

This rule indicates that all "p" elements should be shown in the Arial typeface.

Selectors indicate which element the rule applies to. The same rule can apply to more than one element if you separate the element names with commas.

Declarations indicate how the elements referred to in the selector should be styled. Declarations are split into two parts (a property and a value), and are separated by a colon.


**How to write CSS**
First you need to find the selector you want to apply **CSS** on it like paragraph or anything else like bellow
```
p, h1, h2, li {
    color: #cccccc;
    font-weight: 700; // 700 will give you a Bold text
}
```

![CSS](https://disenowebakus.net/en/images/articles/css-fundamentals-syntax-structure-instruction.jpg)


## How to apply CSS in your page

There are three way to implement your CSS with
1. Inline CSS
2. Add style tag into head and put your css on it
3. External CSS file the link it to you page


You can do you style in head like image below
![Head-Style](https://webdev.imgix.net/codelab-extract-and-inline-critical-css/inline-critical-css.png)

Or you can create new file called style.css and link it with Link in head tag
![CSS-File](https://encrypted-tbn0.gstatic.com/images?q=tbn%3AANd9GcTEa8945FoKgb64v8jcXRvrdOxQ7gkrUUEFqrcaP5Ji69A5HPU1&usqp=CAU)