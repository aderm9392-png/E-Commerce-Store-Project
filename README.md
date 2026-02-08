# ALBARKA STORE - E-Commerce Web Application

A modern, fully-functional e-commerce web application built with vanilla JavaScript, HTML, and CSS. Featuring product management, shopping cart functionality, admin controls, and a respondent design.

## 🌟 Features

- **Product Catalog** - Browse and filter products with detailed descriptions and pricing
- **Shopping Cart** - Add/remove items, manage quantities, view cart totals
- **Admin Panel** - Edit, add, and delete products in demo mode
- **Dark/Light Theme** - Toggle between light and dark modes with persistent preferences
- **Responsive Design** - Mobile-friendly layout that works on all devices
- **Demo Mode** - Editable prices and products for testing (banner indicates status)
- **Trust Signals** - Display average ratings and review counts
- **Analytics Tracking** - Built-in event tracking using localStorage
- **Persistent Storage** - Cart and product data saved to localStorage
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Multiple Pages** - Home, Products, Orders, About, Contact, and Admin sections

## 📁 Project Structure

```
├── index.html              # Main HTML file
├── app.js                  # Main application logic
├── styles.css              # Stylesheet
├── shared-header.html      # Header component
├── shared-footer.html      # Footer component
├── shared-modals.html      # Modal dialogs
├── about.html              # About page
├── contact.html            # Contact page
├── products.html           # Products page
├── orders.html             # Orders page
├── admin.html              # Admin panel
├── robots.txt              # SEO robots file
├── sitemap.xml             # XML sitemap
└── README.md               # This file
```

## 🚀 Getting Started

### Installation

1. Clone or download the project:
```bash
git clone <repository-url>
cd "E Commerce Project"
```

2. No build process or dependencies required! This is a vanilla JavaScript application.

### Usage

1. Open `index.html` in a modern web browser
2. Navigate using the menu or links
3. Add products to your cart
4. Toggle dark/light theme using the moon icon
5. In demo mode, click products to edit them (admin functionality)

## 💡 Demo Mode

The application runs in demo mode with editable products and prices. This allows you to:
- Add new products
- Edit existing product details (name, price, description, quantity, image)
- Delete products
- Test shopping cart functionality

The demo banner at the top indicates when demo mode is active. You can close it with the × button.

## 🛠 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Responsive styling with flexbox/grid
- **Vanilla JavaScript** - No frameworks or libraries
- **LocalStorage API** - Data persistence
- **Responsive Web Design** - Mobile-first approach

## 📊 Key Features Explanation

### State Management
The application uses a centralized state object to manage:
- Products inventory
- Shopping cart items
- Current page view
- Theme preference
- Loading states

### Event Tracking
Built-in analytics that captures:
- User interactions
- Page navigation
- Cart operations
- Product edits
- Timestamps for each event

### Storage
All data is persisted in browser's localStorage:
- Product catalog
- Shopping cart
- Theme preference
- Analytics events
- Admin settings

## 🎨 Customization

### Add Your Products
Edit the `SEED_ITEMS` array in `app.js` to add your own products with:
- Product name and description
- Price and quantity
- Category
- Image URL
- Rating and review count

### Customize Styling
Modify `styles.css` to change:
- Colors and branding
- Typography
- Layout and spacing
- Responsive breakpoints

### Update Meta Information
Edit `index.html` to update:
- Site title and description
- OG tags for social sharing
- Favicon and theme color
- Author information

## 📱 Browser Compatibility

- Chrome/Edge (Latest)
- Firefox (Latest)
- Safari (Latest)
- Mobile browsers

## 📝 Author

Wujdi Mustapha Adam

## 📄 License

[Add your license here]

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Report bugs
2. Suggest features
3. Submit pull requests
4. Improve documentation

---

**Note**: This project uses localStorage for data persistence. All data is stored locally in your browser and is cleared when you clear browser cache. For production use, connect to a backend API and database.
