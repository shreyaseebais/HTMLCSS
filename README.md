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