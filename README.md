# 🍽️ African Delights - Complete African Cuisine Restaurant Website

A comprehensive, fully-functional online restaurant platform featuring authentic African cuisine from 8 African countries with dynamic pages, animations, multiple payment methods, and an interactive shopping cart.

## 📋 Project Overview

**African Delights** is a professional web application showcasing authentic African cuisine with:
- 32 unique traditional dishes across 8 African countries
- Interactive menu with search and filter functionality
- Complete checkout system with 6 payment methods
- Detailed preparation methods and ingredients for all dishes
- Smooth animations and modern UI/UX design
- Fully responsive design (mobile, tablet, desktop)

## 🌍 Featured African Countries

1. **🇧🇯 Benin** - Aromatic soups and flavorful stews
2. **🇨🇮 Ivory Coast** - Rich sauces and premium specialties
3. **🇬🇦 Gabon** - Tropical flavors and palm nut cuisine
4. **🇬🇭 Ghana** - Bold flavors and beloved local favorites
5. **🇸🇳 Senegal** - Elegant dishes and West African heritage
6. **🇨🇲 Cameroon** - Diverse flavors from Central Africa
7. **🇪🇹 Ethiopia** - Legendary spice blends and injera bread
8. **🇳🇬 Nigeria** - Spicy, vibrant flavors and classics

## 📁 Project Structure

```
kenyto/
├── index.html                  # Home page with featured countries
├── css/
│   ├── main.css               # Main styles and navbar
│   ├── animations.css         # 20+ animation effects
│   ├── country-page.css       # Country page styles
│   ├── menu.css               # Menu page styles
│   ├── ordering.css           # Checkout page styles
│   └── about.css              # About page styles
├── js/
│   ├── main.js                # Core functionality (cart, notifications, etc.)
│   ├── menu.js                # Menu filtering and sorting
│   ├── country-page.js        # Country page scripts
│   └── ordering.js            # Checkout and payment handling
├── data/
│   └── meals.js               # Complete meal database with all dishes
├── pages/
│   ├── benin.html             # Benin country page
│   ├── ivory-coast.html       # Ivory Coast country page
│   ├── gabon.html             # Gabon country page
│   ├── ghana.html             # Ghana country page
│   ├── senegal.html           # Senegal country page
│   ├── cameroon.html          # Cameroon country page
│   ├── ethiopia.html          # Ethiopia country page
│   ├── nigeria.html           # Nigeria country page
│   ├── menu.html              # Full menu with filters
│   ├── ordering.html          # Checkout page
│   ├── about.html             # About us page
│   └── confirmation.html      # Order confirmation page
└── images/                    # Placeholder for meal and flag images

```

## 🎨 Color Scheme

- **Primary Color**: #D4A574 (Golden Brown - African Heritage)
- **Secondary Color**: #8B4513 (Saddle Brown - Earthy Tones)
- **Accent Color**: #FF6B35 (Burnt Orange - Energy & Vibrancy)
- **Dark Background**: #1a1a1a
- **Light Background**: #f5f5f5

## 🚀 Getting Started

### Prerequisites
- Web browser (Chrome, Firefox, Safari, Edge)
- No server required - runs entirely in the browser using localStorage

### Installation

1. **Extract the project files** to your desired location
2. **Open index.html** in your web browser (or use a local server)
3. **Navigate through the website** to explore all features

### Running Locally with a Server (Recommended)

**Using Python 3:**
```bash
cd kenyto
python -m http.server 8000
```
Then open: `http://localhost:8000`

**Using Node.js (http-server):**
```bash
npm install -g http-server
cd kenyto
http-server
```

**Using VS Code Live Server:**
- Install Live Server extension
- Right-click index.html → "Open with Live Server"

## ✨ Features

### 1. **Dynamic Navigation**
- Sticky navbar with dropdown menus
- Hamburger menu for mobile devices
- Cart badge showing number of items
- Active page highlighting

### 2. **Home Page**
- Hero section with animated tagline
- Featured countries grid with hover effects
- "How It Works" section
- Testimonials carousel
- Footer with contact information

### 3. **Country Pages (8 Pages)**
- Country-specific information and facts
- Curated dish listings (4 dishes each)
- Traditional cooking techniques showcase
- Beautiful animations on scroll
- Direct ordering buttons on each dish

### 4. **Complete Menu Page**
- Display of all 32 dishes
- **Advanced Filtering**:
  - Filter by country
  - Search by name, description, or ingredient
  - Sort by: Name, Price (Low→High), Price (High→Low), Rating
- Real-time search functionality
- Staggered animation effects
- Add to cart functionality

### 5. **Detailed Meal Cards**
Each meal displays:
- Meal image with rating badge
- Name and country of origin
- Detailed description
- Complete ingredient list
- Step-by-step preparation instructions
- Preparation time
- Number of servings
- Price
- Add to cart button

### 6. **Shopping Cart System**
- Add items with quantity control
- Update item quantities (+ / -)
- Remove items from cart
- Real-time cart total calculation
- Cart persists using browser localStorage
- Cart count badge in navbar

### 7. **Checkout & Ordering System**
Complete order form with:
- **Delivery Information**:
  - Full name, email, phone
  - Delivery address (street, city, state, zip)
  - Special delivery instructions
  - Preferred delivery time (6 time slots)

- **Order Summary**:
  - Itemized order listing
  - Subtotal calculation
  - Shipping fee ($5.00)
  - Tax calculation (8%)
  - Total amount

- **Form Validation**:
  - Real-time field validation
  - Error messages displayed inline
  - Required field indicators
  - Email format validation
  - Phone number validation

### 8. **Payment Methods (6 Options)**

#### 💳 **Credit Card / Debit Card**
- Card number input
- Cardholder name
- Expiry date (MM/YY)
- CVV security code

#### 📱 **Mobile Money**
- Provider selection (MTN, Vodafone, Airtel, Orange)
- Phone number input
- Secure mobile payment flow

#### 🏦 **Bank Transfer**
- Account holder name
- Account number
- Bank name
- SWIFT code
- Manual transfer instructions

#### 🌐 **PayPal**
- PayPal email verification
- Secure PayPal redirect
- Payment confirmation

#### ₿ **Cryptocurrency**
- Bitcoin, Ethereum, USDC support
- Wallet address input
- QR code payment instructions

### 9. **Animations & Effects**
20+ custom animations including:
- Fade in/out
- Slide up/down/left/right
- Bounce
- Float
- Scale up/down
- Spin/rotate
- Glow effects
- Staggered animations for lists
- Smooth transitions on all interactive elements

### 10. **About Us Page**
- Company story and mission
- Core values (Quality, Authenticity, Community)
- Why choose us section
- Team member profiles
- Contact form
- Customer support information

### 11. **Order Confirmation Page**
- Animated success confirmation
- Order ID and details
- Delivery address confirmation
- Order total
- What happens next timeline
- Call to action buttons

## 📱 Responsive Design

The website is fully responsive with breakpoints for:
- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: Below 768px

All pages are optimized for touch interactions on mobile devices.

## 🛒 Meal Database

**32 Total Dishes** with complete information:

### Benin (4 dishes)
- Gari & Soup
- Pâte
- Akasan (Corn Pudding)
- Yam & Fish Stew

### Ivory Coast (4 dishes)
- Attiéké & Grilled Fish
- Foutou Banane
- Kedjenou (Ivorian Stew)
- Aloco (Fried Plantains)

### Gabon (4 dishes)
- Moambe Chicken
- Plantain & Fish Gabonese Style
- Poulet aux Fruits de Mer
- Manioc Fries

### Ghana (4 dishes)
- Jollof Rice
- Waakye
- Fufu with Light Soup
- Kelewele (Spicy Fried Plantains)

### Senegal (4 dishes)
- Thiéboudienne
- Cebbu Jën
- Yassa Chicken
- Accra (Fish Cake)

### Cameroon (4 dishes)
- Ndolé
- Fufu Cameroon
- Okra Soup
- Samosas Cameroon

### Ethiopia (4 dishes)
- Doro Wot (Chicken Stew)
- Injera (Ethiopian Bread)
- Shiro
- Misir Wot (Red Lentil Stew)

### Nigeria (4 dishes)
- Jollof Rice Nigerian
- Egusi Soup
- Pepper Soup
- Suya (Spiced Meat Skewers)

## 💾 Local Storage Usage

The website uses browser localStorage to persist:
- **Shopping cart items** - Cart data survives page refreshes
- **Order history** - Last order saved for confirmation page
- **User preferences** - Potential for future enhancements

Data structure:
```javascript
// Cart items
{
  id: 1,
  name: "Gari & Soup",
  price: 12.99,
  quantity: 2
}

// Last order
{
  id: "ORD-...",
  timestamp: "2026-02-02...",
  customer: { name, email, phone, address, ... },
  items: [...],
  subtotal, shipping, tax, total,
  paymentMethod: "creditCard"
}
```

## 🎯 User Experience Flows

### Browse & Order Flow
1. User lands on home page
2. Explores featured countries
3. Navigates to country page or menu
4. Browses dishes with detailed information
5. Adds items to cart
6. Reviews cart (modal or sidebar)
7. Proceeds to checkout
8. Fills delivery information
9. Selects payment method
10. Reviews order summary
11. Places order
12. Sees confirmation page
13. Receives order confirmation email (simulated)

### Menu Filtering Flow
1. User opens menu page
2. Can search by dish name, ingredient, or cuisine
3. Can filter by country
4. Can sort by name, price, or rating
5. Results update in real-time
6. Staggered animations show results

## 🔒 Security Features

- Form validation on all inputs
- Email format verification
- Phone number validation
- HTTPS ready (implement SSL certificate in production)
- No sensitive data stored locally (except order confirmation for demo)
- Client-side validation as first layer of defense

## 🎬 JavaScript Functionality Highlights

### Main.js (Core Functionality)
- Cart management (add, remove, update quantity)
- localStorage integration
- Form validation utilities
- Notification system
- Payment method configuration
- Meal display functions
- Animation helpers
- Utility functions (formatting, ID generation)

### Menu.js (Menu Page)
- Country filtering
- Search implementation
- Sorting functionality
- Real-time result updates
- Staggered animations

### Ordering.js (Checkout)
- Order summary generation
- Payment method form switching
- Form field validation
- Order submission
- Total calculations

## 📊 Statistics

- **8 Country Pages** - Each with unique content
- **32 Unique Dishes** - Complete with ingredients and preparation
- **6 Payment Methods** - Comprehensive payment options
- **20+ Animations** - Smooth, professional interactions
- **4 Main CSS Files** - Organized, maintainable stylesheets
- **3 Main JS Files** - Modular, functional code
- **100% Responsive** - Works on all devices
- **No Dependencies** - Pure HTML, CSS, JavaScript

## 🎨 Design Highlights

- **Color Psychology**: Uses warm, earthy tones reflecting African heritage
- **Typography**: Clear hierarchy with readable font sizes
- **Spacing**: Consistent padding and margins
- **Shadows**: Subtle depth with professional shadows
- **Hover States**: Interactive feedback on all clickable elements
- **Loading States**: Smooth animations for perceived performance
- **Mobile First**: Optimized for small screens first
- **Accessibility**: Semantic HTML, proper contrast ratios

## 🔧 Customization Guide

### Change Colors
Edit `:root` in `css/main.css`:
```css
:root {
    --primary-color: #D4A574;
    --secondary-color: #8B4513;
    --accent-color: #FF6B35;
    /* ... */
}
```

### Add New Dishes
Edit `data/meals.js`:
```javascript
ghana: [
    {
        id: 40,
        name: "New Dish",
        country: "Ghana",
        price: 14.99,
        category: "Main Course",
        image: "images/...",
        rating: 4.8,
        reviews: 42,
        description: "...",
        ingredients: [...],
        prepTime: "40 minutes",
        servings: "2-3 people",
        preparation: [...]
    }
]
```

### Add New Payment Method
Edit `js/main.js` in `paymentMethods` object and add corresponding form in `showing.html`.

### Change Text/Copy
All text is in HTML files - simply edit the content directly.

## 📝 Notes

- **Images**: Replace placeholder image paths with actual meal images
- **Email**: No actual email sending implemented (for demo purposes)
- **Payment Processing**: Payment forms collect data but don't process (for demo)
- **Database**: Data stored in JavaScript object, could be replaced with backend API
- **Authentication**: No user authentication (could be added)

## 🚀 Production Deployment

To deploy this website:

1. **Add real images** for all dishes
2. **Implement backend API** for:
   - Order processing
   - Payment gateway integration (Stripe, PayPal, etc.)
   - Email confirmation system
   - User authentication
3. **Set up web hosting** (Netlify, Vercel, GitHub Pages, etc.)
4. **Enable HTTPS** (SSL certificate)
5. **Add analytics** (Google Analytics)
6. **Set up database** for:
   - Orders
   - User accounts
   - Inventory management
7. **Implement admin dashboard** for managing:
   - Orders
   - Menu items
   - Deliveries

## 📞 Support & Contact

**Email**: info@africandelights.com
**Phone**: +1 (555) 123-4567
**Hours**: Mon-Sun 10AM-10PM

## 📄 License

This project is a demonstration/educational project. Feel free to customize and use as needed.

## 🙏 Acknowledgments

- Authentic African cuisine research
- Beautiful animations and modern UI/UX design
- Comprehensive payment integration options
- Mobile-first responsive design approach

---

**Enjoy exploring authentic African cuisine with African Delights! 🍽️🌍**
