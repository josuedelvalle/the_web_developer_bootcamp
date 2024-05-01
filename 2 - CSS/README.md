# CSS

CSS, *Cascading Style Sheets*, is a language for describing how documents are presented visually - how they are arranged and styled.

CSS is very easy to get the hang of,  but it can be intimidating because of how many properties we can manipulate.

Whenever we write CSS, we are writing **CSS rules**. Almost everything you do in CSS follows this basic pattern:
```
selector {
    property: value;
}
```

For example, this is how we would modify the color of all the `h2` elements on our page and the `image` elements size:
```
h2 {
    color: purple;
}

img {
    width: 100px;
    height; 200px;
}
```

There are tons of properties what you can use at any point. That does not mean you need to know them all at once or that you need to memorize them. Nobody expects you to be a master of every single property - the ones that you use the most you'll just naturally come to remember, but the ones you don't use or very frequently use, you'll just look them up. None of it is terribly complicated, fortunately, but there's just a lot.

CSS documentation 👉 [CSS reference - MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

---

The CSS content is divided into these sections:

1. [The very basics](/2%20-%20CSS/1%20-%20The%20very%20basics/)

   > Basic CSS Syntax | Including Style Correctly | Color Systems | Common Text Properties | Font-Family Property

2. [The World of CSS Selectors](/2%20-%20CSS/2%20-%20CSS%20Selectors/)

   > Universal and Element Selectors | ID Selector | Class Selector | Descendant Selector | Adjacent and Direct-Descendant Selector | Attribute Selector | Pseudo Classes and Elements | CSS Cascade | CSS Specificity | Inline Styles and Important | CSS Inheritance
    👉 [CSS selector exercises](/2%20-%20CSS/2%20-%20CSS%20Selectors/Exercises/)

3. [The CSS Box Model](/2%20-%20CSS/3%20-%20Box%20model/)

   > Box Model: Width and Height; Border and Border-Radius; Padding; Margin | Display Property | CSS Units: ems and rems

4. [Other Assorted Useful CSS Properties](/2%20-%20CSS/4%20-%20Other%20CSS%20properties/)

   > Opacity & Alpha Channel | Position | Transitions | Transforms | Background | Google Fonts

5. [Responsive CSS & Flexbox](/2%20-%20CSS/5%20-%20Flexbox%20and%20responsive/)

   > Flexbox: Flex-Direction, Justify-Content, Flex-Wrap, Align-Items, Align-Content, Align-Self, Flex-Basis/Grow/Shrink, Flex Shorthand | Media Queries