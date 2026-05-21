# Web Technologies First Assignment

This repository contains a front-end web assignment for a UCLan merchandise website. The project is built with HTML, CSS, and JavaScript, and includes a small product shop where users can view products, add items to a cart, update quantities, remove items, clear the cart, and apply an offer code.

## Project Overview

The website is based on a UCLan web page and product store. It includes a home page with embedded video content, a products page with UCLan legacy T-shirts, individual product detail pages, and a shopping cart page.

## Features

- Home page with UCLan branding and video content
- Responsive navigation with a hamburger menu
- Products page displaying nine T-shirt products
- Product detail page loaded using the product ID in the URL
- Add to cart functionality
- Cart data saved using browser localStorage
- Quantity updates inside the cart
- Remove individual cart items
- Clear the whole cart
- Cart total calculation
- Offer code support using `save10` for 10% off
- Product images and local video asset included

## Pages

| Page | File | Description |
| --- | --- | --- |
| Home | `index.html` | Main landing page with UCLan branding and video content |
| Products | `products.html` | Displays all available T-shirt products |
| Product Details | `Items.html` | Shows details for a selected product using a URL ID |
| Cart | `cart.html` | Displays cart items, totals, quantity controls, and offer code input |

## Technologies Used

- HTML5
- CSS3
- JavaScript
- Browser localStorage

## File Structure

```text
.
|-- index.html
|-- products.html
|-- Items.html
|-- cart.html
|-- style.css
|-- cart.js
|-- index.js
|-- product-array.html
|-- iframe_link.url
|-- video.mp4
|-- images/
|   |-- logo.png
|   |-- logo_reverse.png
|   `-- tshirts/
|       |-- tshirt1.jpg
|       |-- tshirt2.jpg
|       |-- tshirt3.jpg
|       |-- tshirt4.jpg
|       |-- tshirt5.jpg
|       |-- tshirt6.jpg
|       |-- tshirt7.jpg
|       |-- tshirt8.jpg
|       `-- tshirt9.jpg
`-- README.md
```

## How to Run the Project

No installation is required because this is a static front-end website.

1. Download or clone the repository.
2. Open the project folder in VS Code.
3. Open `index.html` in a browser.

You can also run it with the VS Code Live Server extension for a smoother development experience.

## How to Use the Cart

1. Go to the `Products` page.
2. Choose a quantity for a product.
3. Click `Add to Cart`.
4. Open the `Cart` page to view the selected products.
5. Update item quantities or remove items if needed.
6. Enter `save10` in the offer code box to apply a 10% discount.

## Repository

GitHub repository:

```text
https://github.com/GeorgeConstantinou23/web-technologies--firstAssignment
```

## Author

George Constantinou

## Notes

- Cart items are stored in the browser, so the cart may be different on another browser or computer.
- Clearing browser storage will remove the saved cart.
- This project was created as part of a Web Technologies assignment.
