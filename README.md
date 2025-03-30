# Shopee Clone

A responsive e-commerce website clone of Shopee built with HTML and CSS. This project replicates the core UI functionality and design of the Shopee e-commerce platform.

## Features

- 🛍️ Product Grid Layout
  - Responsive product cards
  - Product images, prices, and ratings
  - Sale badges and discounts
  - Favorite/Like functionality
  
- 🔍 Search & Navigation
  - Search bar with history
  - Category navigation
  - Product filtering options
  - Sorting by popularity, newest, bestselling
  - Price range filtering
  - Pagination

- 🛒 Shopping Cart
  - Add/Remove products
  - Quantity adjustment
  - Cart notifications
  - Empty cart state handling

- 👤 User Features
  - Login/Register forms
  - Social login options (Facebook, Google)
  - User profile menu
  - Notification center

- 📱 Mobile Integration
  - QR code for app download
  - App store links (iOS & Android)
  - Mobile-first responsive design

## Tech Stack

- HTML5
- CSS3 (with Grid system)
- Font Awesome Icons
- Normalize.css

## Project Structure

```
.
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   ├── base.css       # Base styles and utilities
│   │   ├── grid.css       # Grid system
│   │   └── main.css       # Main component styles
│   └── img/
│       ├── Appstore.png   # iOS app store image
│       ├── GGPlay.png     # Google Play store image
│       ├── QR.png         # QR code for app
│       └── no-cart.png    # Empty cart image
```

## CSS Organization

- `base.css`: Contains base styles, variables, and utility classes
- `grid.css`: Implements the responsive grid system
- `main.css`: Contains component-specific styles

## Grid System

The project uses a custom grid system with the following breakpoints:

- Mobile: Default
- Tablet: 740px -> 1023px
- PC: 1024px+

## Running the Project

1. Clone the repository
2. Open `index.html` in your browser
3. No build process or dependencies required

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
