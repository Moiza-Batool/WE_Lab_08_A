# Sweet Bites - E-Commerce Dessert Shop
A responsive **E-Commerce Dessert Shop** built with **HTML5**, **CSS3 Grid**, and **JavaScript**. The page displays nine dessert products in an auto-responsive grid that adjusts to any screen size **without using media queries**, includes hover animations on every product card, and updates a cart counter when items are added.

## Features
1. Responsive product gallery built with CSS Grid
2. Auto-adjusting columns using `repeat(auto-fit, minmax(250px, 1fr))`
3. Minimum card width of 250px
4. No explicit media queries
5. Nine dessert product cards with image, name, description, and price
6. Card lift and shadow animation on hover
7. Image zoom effect on hover
8. Cart counter that increases when Add to Cart is clicked
9. Version controlled using Git and hosted on GitHub

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
The page uses **CSS Grid** to arrange the product cards.

The grid is defined by:
* `display: grid`
* `grid-template-columns: repeat(auto-fit, minmax(250px, 1fr))`
* `gap: 20px`

How it adapts:
* Wide screens show three or more cards per row
* Tablets show two cards per row
* Phones show one card per row

## How It Works
1. `index.html` defines the navigation bar, the product cards, and the footer.
2. `style.css` turns the product container into a CSS Grid.
3. `minmax(250px, 1fr)` keeps each card at least 250px wide.
4. `auto-fit` fits as many columns as the screen allows.
5. The `:hover` rules apply the lift, shadow, and zoom effects.
6. A small JavaScript script adds 1 to the cart count each time Add to Cart is clicked.
7. The project is tracked with Git and pushed to a GitHub repository.

## How to Run
1. Clone the repository.
git clone <your-repository-link>

2. Navigate to the project folder.
cd E-commerce_Dessert_Shop

3. Open the page in a browser.
Double-click `index.html`, or right-click it in VS Code and choose Open with Live Server.

4. Resize the browser window to see the grid adjust, and click Add to Cart to see the counter change.

## Output
A responsive dessert shop page where the product cards rearrange themselves according to the screen width, animate on hover, and update the cart counter when items are added.

## 👩‍💻 Author
**Moiza Batool**