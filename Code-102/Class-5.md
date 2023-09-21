[Solar System](https://andtran10.github.io/hello-world/)
# CSS
What is CSS?
- Specifying how documents are presented to users (styling)
    - Color
    - size
    - font
Ruleset:
- Selector: {} : this selects the html element to be styled
- Property: What are we changing : Color, font
- Value: What are we changing the property into

``` 
h1 {
    color: red;
    font-size: 5em;
}
```
# How to add CSS

Three ways to insert CSS
- External CSS
    - ```<link>``` Must be placed within ```<head></head>``` section
    - ```<head> <link rel="Stylesheet" href="file.css">```

    - Pulls info from external .css file and
 applies to html file
    
- Internal CSS
    - ```<style></style>```

    - HTML page with unique style
    - if all heading (or whatever you are changing) is set to one color/style then remaining same heading in page will be the same

- Inline CSS
    - ```<style> self closing```
    - Apple style to a single element

    - ```<h1 style="color:blue;>This is a heading``` This heading will turn blue

Cascading order: if multiple style sheets are present

1. Inline Style (inside an HTML element)

1. External and internal (what appears last or at the bottom of head section)
1. Browser default

# Color

- color: red

Hex value:

- color: #00ff00

RGB (red, green, blue) value:

- color: rgb(0,0,225)

HSL (hue, saturation, lightness) value:

- color: hsl(170, 50%, 50%)

HSLA (hue, saturation, lightness, alpha) (alpha = transparency 0.0 - 1.0):

- color: hsla(120, 100%, 40%, 0.7)

# Questions:
1. What is the purpose of CSS?
    - To style and layout web pages

1. What are the three ways to insert CSS into your project?
    - External CSS
    - Internal CSS
    - Inline CSS

1. Write an example of a CSS rule that would give all ```<p>``` elements red text?
    ```
    p {
        color: red;
    }
    ```

