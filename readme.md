# Responsive Image Grid Layout

This project is an example implementation of a responsive image gallery built purely with **CSS Grid Layout**. The gallery displays 6 images with a layout that dynamically adapts to different device screen sizes (Desktop, Tablet, and Mobile).

## 🚀 Key Features

* **CSS Grid Areas**: Uses the `grid-template-areas` property to arrange the layout of each image (`box-1` to `box-6`) specifically and neatly.

* **Responsive Design**: Utilizes *Media Queries* to adjust the number of columns and image placement across 3 different breakpoints:

  * **Small Screen / Mobile** (Max 600px): The grid transforms into 2 columns with adjusted grid areas.

  * **Medium Screen / Tablet** (601px - 768px): The grid uses 3 columns with a different area pattern compared to the desktop view.

  * **Large Screen / Desktop** (Screens > 768px): The default grid pattern with proportional sizing.

* **Image Cover**: Images will not be distorted or stretched even when the container size changes, thanks to the `object-fit: cover` property.

## 📁 File Structure

* `index.html` - The main HTML structure and container for the images.

* `styles.css` - The main styling file containing the CSS Grid logic and media queries.

*Note: Ensure you have an `images/` folder in the same directory as these files, containing `gunung-1.jpg` to `gunung-6.jpg`, so the images render correctly.*

## 🛠️ How to Run

1. Clone or download this project code.

2. Ensure your image files are available in the `images` folder.

3. Open the `index.html` file using a web browser (Google Chrome, Firefox, Safari, etc.).

4. Try resizing the browser window to see the responsive effects of the CSS Grid.

## 🔗 Learning References

To deepen your knowledge of Web Development (such as CSS, HTML, and comprehensive Frontend learning paths), you can follow the free guides here:

* [Roadmap.sh - Developer Roadmaps](https://roadmap.sh/projects/image-grid)