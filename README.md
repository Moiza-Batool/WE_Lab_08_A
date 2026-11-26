# Sweet Bites - E-Commerce Dessert Shop
A responsive **E-Commerce Dessert Shop** built with **HTML5**, **CSS3 Grid**, and **JavaScript**. The page uses a dashboard layout with a header, sidebar, main content, two widgets, and a footer. It displays nine dessert products in an auto-responsive grid that adjusts to any screen size **without using media queries**, includes hover animations on every product card, and updates a cart widget when items are added.

## Features
1. Dashboard layout built with CSS Grid template areas
2. Responsive product gallery built with CSS Grid
3. Auto-adjusting columns using `repeat(auto-fit, minmax(250px, 1fr))`
4. Minimum card width of 250px
5. No explicit media queries
6. Nine dessert product cards with image, name, description, and price
7. Card lift and shadow animation on hover
8. Image zoom effect on hover
9. Click any picture to open it in a larger image viewer
10. Sidebar with hover effect and options: Contact Us, Offers, My Orders, Log Out
11. Sidebar option to view products with or without pictures
12. Cart widget with item counter, last added item, and clear button
13. About widget with shop information
14. Version controlled using Git and hosted on GitHub

## Technical Stack
* HTML5
* CSS3 (Grid Layout)
* JavaScript
* Git
* GitHub
* VS Code

## Project Structure
E-commerce_Dessert_Shop/
│
├── index.html
├── style.css
├── README.md
├── macarons.jpg
├── sheet-cakes.jpg
├── oreo-pudding.jpg
├── donuts.jpg
├── mochi.jpg
├── tanghulu.jpg
├── tiramisu.jpg
├── cookies.jpg
└── blueberry-mini-cakes.jpg

## Products
The gallery contains nine dessert items:
* French Macarons
* Sheet Cakes
* Oreo Pudding
* Assorted Donuts
* Japanese Mochi
* Fruit Tanghulu
* Tiramisu
* Chocolate Chip Cookies
* Blueberry Mini Cakes

Each product card displays:
* Product image
* Product name
* Short description
* Price
* Add to Cart button

## Layout
The page uses **CSS Grid** in two levels.

The dashboard is defined by `grid-template-areas`:
* Header across the top
* Sidebar on the left
* Main content in the centre
* Widget A (Cart) and Widget B (About) below the main content
* Footer across the bottom

The product grid inside the main content is defined by:
* `display: grid`
* `grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))`
* `gap: 20px`

How it adapts:
* Wide screens show three or more cards per row
* Tablets show two cards per row
* Phones show one card per row

## Sidebar
* **With Pictures:** shows the product cards with images (default)
* **Without Pictures:** hides the images and shows text-only cards, the hover effect still works
* **Contact Us:** jumps to the About widget
* **Offers, My Orders, Log Out:** placeholder menu links

## How It Works
1. `index.html` defines the header, sidebar, product cards, widgets, and footer.
2. `style.css` creates the dashboard layout with `grid-template-areas` and turns the product container into a CSS Grid.
3. `minmax(250px, 1fr)` keeps each card at least 250px wide.
4. `auto-fit` fits as many columns as the screen allows.
5. The `:hover` rules apply the lift, shadow, zoom, and sidebar highlight effects.
6. A small JavaScript script updates the cart widget each time Add to Cart is clicked.
7. JavaScript also switches the product grid between the with-pictures and without-pictures views.
8. Clicking a picture opens it in an image viewer, which closes with the × button, a click outside the image, or the Esc key.
9. The project is tracked with Git and pushed to a GitHub repository.

## How to Run
1. Clone the repository.
git clone <your-repository-link>

2. Navigate to the project folder.
cd E-commerce_Dessert_Shop

3. Open the page in a browser.
Double-click `index.html`, or right-click it in VS Code and choose Open with Live Server.

4. Resize the browser window to see the grid adjust, click Add to Cart to see the cart widget change, click a picture to open it, and use the sidebar to switch the view.

## Output
A responsive dessert shop dashboard where the product cards rearrange themselves according to the screen width, animate on hover, can be viewed with or without pictures, and update the cart widget when items are added.

## 👩‍💻 Author
**Moiza Batool**