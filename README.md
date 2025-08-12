# CHAMAN KNIT KIDS - Order Taking App

Hello friends! I have created an order taking app which is very easy to use and update.

## Features
- Browse products from Excel file
- Add products to cart with quantity selection
- Customer information collection (name and mobile)
- Generate PDF order summary
- Send orders directly to WhatsApp (919855283523)
- Responsive design for mobile and desktop

## How to Run the App

### Method 1: Using npm (Recommended)
```bash
npm install
npm run dev
```
Then open your browser to the URL shown in the terminal (usually http://localhost:3000)

### Method 2: Direct Browser Access
Simply open the `index.html` file directly in your web browser by double-clicking it.

## How to Update Products

1. Update the `products.xlsx` file with your product information
2. The Excel file should have columns for:
   - Product name (product/Product/name/Name)
   - Category (category/Category/type/Type)
   - Price (price/Price/cost/Cost)
   - Description (description/Description/details/Details)
   - Image URL (image/Image/photo/Photo)

3. New products will be automatically listed when you refresh the app

## Usage Instructions

1. **For Customers:**
   - Browse products by category or search
   - Click "Add to Cart" with desired quantity
   - Review cart by clicking the cart icon
   - Enter name and mobile number
   - Click "Send Order to WhatsApp"

2. **For Business Owner:**
   - Orders will be sent to WhatsApp number: 919855283523
   - Each order includes customer details and PDF summary
   - Update products by modifying the Excel file

## Technical Details

- Pure HTML/CSS/JavaScript application
- Uses external CDN libraries for Excel reading and PDF generation
- No server required - runs entirely in the browser
- Mobile-responsive design
- WhatsApp Web API integration

## File Structure
```
├── index.html          # Main application file
├── products.xlsx       # Product catalog (update this file)
├── package.json        # npm configuration
└── README.md          # This file
```