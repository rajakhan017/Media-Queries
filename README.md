# Media-Queries
# Assignment

## [Live Website Link!]https://rajakhan017.github.io/Media-Queries/

### Web/Desktop UI Structure

img src="./assets/readme/web-ui.png" width="700px" alt="structure of the web UI"  

### Mobile UI Structure

img src="./assets/readme/mobile-ui.png" width="250px" alt="structure of the mobile UI"  

### Tablet Structure

img src="./assets/readme/tablet-ui.png" width="500px" alt="structure of the tablet UI" 

---

### CSS Explanation:

#### `*`

| Property    | Value              | Explanation                                                                             |
| ----------- | ------------------ | --------------------------------------------------------------------------------------- |
| margin      | 0                  | Sets the margin of all elements to 0.                                                   |
| box-sizing  | border-box         | Specifies that padding and border are included in the element's total width and height. |
| font-family | Roboto, sans-serif | Defines the font family for all elements.                                               |

Explanation: The `*` selector targets all elements on the page, applying these CSS properties to all elements.
![image](https://github.com/rajakhan017/Media-Queries/assets/135150598/8e347792-73b9-4064-8802-96cb4a81750a)

#### `body`

| Property            | Value                | Explanation                                                  |
| ------------------- | -------------------- | ------------------------------------------------------------ |
| height              | 100vh                | Sets the height of the body to 100% of the viewport height.  |
| width               | 90%                  | Sets the width of the body to 90% of its containing element. |
| max-width           | 1200px               | Limits the maximum width of the body to 1200 pixels.         |
| display             | grid                 | Uses grid layout for the body.                               |
| grid-template-areas | 'image main'         | Defines the grid template areas for child elements.          |
| place-content       | center               | Centers the content within the grid container.               |
| align-items         | center               | Vertically centers items within the grid container.          |
| margin              | auto                 | Centers the body horizontally using auto margins.            |
| background          | linear-gradient(...) | Applies a linear gradient background to the body.            |

Explanation: The `body` selector styles various aspects of the page body, including layout and background.
![image](https://github.com/rajakhan017/Media-Queries/assets/135150598/85286b21-fa13-4402-b2db-59f4dfec4dd6)

#### `.image`

| Property  | Value | Explanation                                                          |
| --------- | ----- | -------------------------------------------------------------------- |
| grid-area | image | Specifies the grid area for the `.image` element.                    |
| width     | 25vw  | Sets the width of the `.image` element to 25% of the viewport width. |

Explanation: The `.image` class is used for styling the image element within the grid layout.

#### `.main`

| Property   | Value  | Explanation                                      |
| ---------- | ------ | ------------------------------------------------ |
| grid-area  | main   | Specifies the grid area for the `.main` element. |
| text-align | center | Centers the text within the `.main` element.     |

Explanation: The `.main` class is used for styling the main content within the grid layout.

#### `h1`

| Property    | Value          | Explanation                                                   |
| ----------- | -------------- | ------------------------------------------------------------- |
| font-size   | 3rem           | Sets the font size of `h1` elements to 3 rem units.           |
| margin      | 2rem auto 1rem | Sets margins for `h1` elements.                               |
| width       | 35vw           | Sets the width of `h1` elements to 35% of the viewport width. |
| line-height | 1              | Sets the line height of `h1` elements to 1.                   |

Explanation: The `h1` selector styles the header text.
![image](https://github.com/rajakhan017/Media-Queries/assets/135150598/7c305187-bee4-4e2f-89fc-31f9190754dd)

#### `p`

| Property    | Value                   | Explanation                                          |
| ----------- | ----------------------- | ---------------------------------------------------- |
| font-family | 'Open Sans', sans-serif | Defines the font family for `p` elements.            |
| font-weight | 700                     | Sets the font weight of `p` elements to 700.         |
| font-size   | 0.9rem                  | Sets the font size of `p` elements to 0.9 rem units. |
| line-height | 1.3                     | Sets the line height of `p` elements to 1.3.         |
| margin      | 0 auto 1.7rem           | Sets margins for `p` elements.                       |

Explanation: The `p` selector styles paragraph text.

#### `span`

| Property      | Value          | Explanation                                           |
| ------------- | -------------- | ----------------------------------------------------- |
| border-bottom | 2px solid #000 | Adds a 2-pixel solid black border to `span` elements. |

Explanation: The `span` selector adds a border to the bottom of specified elements.

#### `button`

| Property         | Value                   | Explanation                                              |
| ---------------- | ----------------------- | -------------------------------------------------------- |
| background-color | #000                    | Sets the background color of `button` elements to black. |
| color            | #fff                    | Sets the text color of `button` elements to white.       |
| font-family      | 'Open Sans', sans-serif | Defines the font family for `button` elements.           |
| font-weight      | 300                     | Sets the font weight of `button` elements to 300.        |
| letter-spacing   | 2px                     | Adds 2 pixels of letter spacing to `button` text.        |
| border           | none                    | Removes the border of `button` elements.                 |
| outline          | none                    | Removes the outline (focus border) of `button` elements. |
| padding          | 0.75rem 3.5rem          | Sets padding for `button` elements.                      |
| margin-top       | -0.5rem                 | Adjusts the top margin of `button` elements.             |

Explanation: The `button` selector styles button elements.

#### Media Query (max-width: 1024px)

| Property   | Value                | Explanation                                                       |
| ---------- | -------------------- | ----------------------------------------------------------------- |
| gap        | 2rem                 | Adds a 2-rem gap between child elements of `body`.                |
| background | linear-gradient(...) | Applies a linear gradient background to `body`.                   |
| width      | 30vw                 | Sets the width of `.image` elements to 30% of the viewport width. |
| font-size  | 2rem                 | Sets the font size of `h1` elements to 2 rem units.               |

Explanation: These styles are applied when the viewport width is less than or equal to 1024 pixels.
![image](https://github.com/rajakhan017/Media-Queries/assets/135150598/36cef0bd-09a6-4804-8662-dd3d627157c3)

#### Media Query (max-width: 768px)

| Property   | Value                | Explanation                                                       |
| ---------- | -------------------- | ----------------------------------------------------------------- |
| gap        | 1rem                 | Adds a 1-rem gap between child elements of `body`.                |
| background | linear-gradient(...) | Applies a linear gradient background to `body`.                   |
| width      | 55vw                 | Sets the width of `.image` elements to 55% of the viewport width. |
| font-size  | 2rem                 | Sets the font size of `h1` elements to 2 rem units.               |

Explanation: These styles are applied when the viewport width is less than or equal to 768 pixels.

#### Media Query (max-width: 640px)

| Property            | Value                | Explanation                                                         |
| ------------------- | -------------------- | ------------------------------------------------------------------- |
| grid-template-areas | 'image' 'main'       | Changes the grid template areas for `body`.                         |
| background          | linear-gradient(...) | Applies a linear gradient background to `body`.                     |
| height              | 55vh                 | Sets the height of `.image` elements to 55% of the viewport height. |
| width               | auto                 | Allows `.image` elements to adjust their width automatically.       |
| margin              | 0.5rem auto 0        | Sets margins for `.image` elements.                                 |
| width               | 90vw                 | Sets the width of `.main` elements to 90% of the viewport width.    |
| font-size           | 1.5rem               | Sets the font size of `h1` elements to 1.5 rem units.               |
| font-size           | 0.7rem               | Sets the font size of `p` elements to 0.7 rem units.                |

Explanation: These styles are applied when the viewport width is less than or equal to 640 pixels.
