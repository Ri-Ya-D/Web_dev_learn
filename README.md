Task 4 – Image & Button Display Page

 Product Description
This is a simple static HTML page that displays an image alongside a styled button. It is built as a front‑end exercise (task_4) to practice basic CSS layout, styling techniques, and integration of external fonts. 
The page uses a centered container with a fixed aspect‑ratio, a responsive image, and a decorative button with a linear gradient background.

 How to Use
1. Open the page – Simply open the `index.html` file in any modern web browser (e.g., Chrome, Firefox, Edge).
2. View the content – The page will show a single image (loaded from the local file `download (1).jpg`) and a button labelled “Click Here”.
3. Interact – The button is a standard `<button>` element; however, no JavaScript is attached, so clicking it will have no effect (this is intentional for the design exercise).
4. Customize – To replace the image, edit the `src` attribute of the `<img>` tag in `index.html` and place your own image in the same directory. To adjust styling, modify the rules in `style.css`.

 Documentation of Purpose
This project serves as a learning exercise in front‑end development, focusing on:

1.CSS Box Model – The container (`<div>`) uses `width: 50vw`, `margin-left/right: 25vw`, and `box-sizing: border-box` to center itself horizontally. The `height: 80vh` and `margin-top: 10%` create vertical spacing.
2.Responsive Image – The image is set to `display: block; width: 100%;` so it fills its parent container while maintaining its aspect ratio.
3.Styling Buttons – Demonstrates the use of `background-image` with a linear gradient, custom borders, and the `Syne Mono` font from Google Fonts.
4.Layout Debugging – The CSS includes a comment about a margin issue (`margin-bottom: 10;` – missing unit) which highlights common pitfalls when using percentages vs. fixed values.
5.External Resources – Shows how to link external stylesheets and Google Fonts.
