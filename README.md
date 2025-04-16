# Farmly E-Commerce Platform

![Farmly Logo](images/wheat.png)

Farmly is an e-commerce platform connecting farmers directly with consumers, offering fresh farm products online with a complete shopping experience.

## Table of Contents
- [Features](#features)
- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Technologies Used](#technologies-used)
- [Folder Structure](#folder-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- 🛒 **Product Catalog** - Browse farm-fresh products
- 🛍️ **Shopping Cart** - Add/remove items, adjust quantities
- 💳 **Checkout System** - Simulated payment processing
- 👥 **User Authentication** - Login/registration forms
- 📍 **Farm Information** - Partner farm profiles
- 📱 **Responsive Design** - Works on all devices
- 📦 **Local Storage** - Cart persists between sessions

## Demo

[Live Demo](https://youtu.be/5YKOtZkW58Q)

![Screenshot](images/screenshot.png)

## Installation

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- Code editor (VS Code recommended)
- Git (for version control)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Elijahbk/farmly_website.git
   cd farmly_website
   ```

2. Install Live Server extension in VS Code (recommended) or use Python's HTTP server:
   ```bash
   python -m http.server 8000
   ```

3. Open in browser:
   - VS Code: Right-click `index.html` → "Open with Live Server"
   - Python server: Visit `http://localhost:8000`

## Usage

### Key Pages
- **Homepage** (`index.html`) - Main landing page with featured products
- **Products** (`product.html`) - Full product catalog
- **Farms** (`blog.html`) - Information about partner farms
- **Cart/Checkout** (`payment.html`) - Shopping cart and payment
- **Login** (`login.html`) - User authentication
- **Contact** (`contact.html`) - Contact form and information

### Shopping Flow
1. Browse products on `/product.html`
2. Click "Buy Now" to add to cart
3. View cart by clicking cart icon (top-right)
4. Proceed through checkout on `/payment.html`

## Configuration

### Google Maps API
1. Get API key from [Google Cloud Console](https://console.cloud.google.com/)
2. Replace in all HTML files:
   ```html
   <script src="https://maps.googleapis.com/maps/api/js?key=YOUR_API_KEY&callback=myMap"></script>
   ```

### Payment Processing
For real payments, integrate with:
- Stripe
- PayPal
- Other payment gateways

## Technologies Used

- **Frontend**
  - HTML5
  - CSS3
  - JavaScript (ES6)
  - Bootstrap 4
  - jQuery 3.4.1
  - Font Awesome

- **Tools**
  - Git
  - VS Code
  - Google Maps API

## Folder Structure

```
farmly-ecommerce/
├── css/               # Stylesheets
│   ├── bootstrap.css
│   ├── font-awesome.min.css
│   ├── responsive.css
│   └── style.css
├── images/            # All images
│   ├── products/      # Product images
│   ├── farms/         # Farm images
│   └── wheat.png      # Favicon
├── js/                # JavaScript files
│   ├── bootstrap.js
│   ├── custom.js      # Custom scripts
│   └── jquery-3.4.1.min.js
├── about.html         # About page
├── blog.html          # Farms page
├── contact.html       # Contact page
├── index.html         # Homepage
├── login.html         # Login/Register
├── payment.html       # Checkout
├── product.html       # Products
└── README.md          # This file
```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE` for more information.

## Contact

Project Link: [https://farmlyapp.netlify.app/](https://farmlyapp.netlify.app/)

For questions or support:
- Email: info@farmly.com
- Phone: +250 780 000 000
- Address: 123 Farm Road, Kigali, Rwanda

---
