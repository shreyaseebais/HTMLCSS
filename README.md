# HTMLCSS

### Table of Contents

| No. | Questions                                                                                       |
| --- | ------------------------------------------------------------------------------------------------| 
| 1 | [](#)                                                                                             |
| 2 | [](#)                                                                                             |
| 3 | [](#)                                                                                             |
| 4 | [](#)                                                                                             |
| 5 | [](#)                                                                                             |
| 7 | [](#)                                                                                             |
| 8 | [](#)                                                                                             |
| 9 | [](#)                                                                                             |
| 10 | [](#)                                                                                            |




**[⬆ Back to Top](#table-of-contents)**

----------------------------------------------------------------------------------------------------------------------
1. ### How to Stretch Elements to Fit the Whole Height of the Browser Window Using CSS?
To stretch elements to fit the whole height of the browser window using CSS, you can use "vh" units, where "1vh" equals 1% of the viewport height, so setting the height to "100vh" spans the entire height.

```html
    <!DOCTYPE html>
    <html>

    <head>
        <style>
            * {
                box-sizing: border-box;
            }

            html,
            body {
                height: 100%;
                margin: 0;
            }

            .stretchElement {
                height: 100vh;
                background: green;
                color: white;
                font-size: 35px;
                padding: 40px;
            }
        </style>
    </head>

    <body>
        <div class="stretchElement">This div will cover whole height of the window.</div>
    </body>

    </html>
```


### 2. What is the difference between relative, absolute, and fixed positioning?

relative: Positioned relative to its normal position.
absolute: Positioned relative to the nearest positioned ancestor.
fixed: Positioned relative to the viewport.


### 3. What is the difference between > and (space) in CSS selectors?

 ' > ' selects direct children, while (space) selects all descendants.


### 4. What is the difference between border-box and content-box?

content-box: Width/height includes only the content.
border-box: Width/height includes content, padding, and border.


### 5. What is the difference between inline, block, and inline-block elements?

inline: Does not start on a new line and only takes up as much width as necessary.
block: Starts on a new line and takes up the full width.
inline-block: Like inline, but allows setting width and height.

### 6. What is Flexbox in CSS?

Flexbox is a layout model for arranging elements in a single dimension (row or column).

Commonly used flex-box properties:
* display: flex;
* justify-content, align-items, align-self
* flex-grow, flex-shrink, flex-basis

### 7. What is CSS Grid, and how is it different from Flexbox?

CSS Grid is for two-dimensional layouts (rows and columns). Flexbox is better suited for one-dimensional layouts.

### 8. What is the difference between em and rem units in CSS?

* em: Relative to the font-size of the parent element.
* rem: Relative to the font-size of the root element (<html>).


### 9. What are media queries?

Media queries allow applying styles based on screen size or device type.
```css
    @media (max-width: 768px) {
        body {
            background-color: lightblue;
        }
    }
```