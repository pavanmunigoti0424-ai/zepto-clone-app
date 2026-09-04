# Zepto Clone App 🛒

A quick commerce delivery mobile app similar to Zepto, built with React Native and Expo.

## Features

- ✅ **Home Screen** - Browse products by categories
- ✅ **Search** - Search for products
- ✅ **Shopping Cart** - Add items and manage quantities
- ✅ **User Account** - Profile, orders, and settings
- ✅ **Bottom Tab Navigation** - Easy navigation between screens
- ✅ **Responsive Design** - Works on iOS and Android

## Tech Stack

- **Framework**: React Native
- **Platform**: Expo
- **Navigation**: React Navigation
- **Icons**: React Native Vector Icons
- **HTTP Client**: Axios

## Prerequisites

- Node.js (v14+)
- npm or yarn
- Expo CLI (`npm install -g expo-cli`)

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/pavanmunigoti0424-ai/zepto-clone-app.git
   cd zepto-clone-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the app**
   ```bash
   npm start
   ```

   Then:
   - Press `i` for iOS simulator
   - Press `a` for Android emulator
   - Scan QR code with Expo Go app (on physical device)

## Project Structure

```
zepto-clone-app/
├── screens/
│   ├── HomeScreen.js       # Browse products & categories
│   ├── SearchScreen.js     # Search products
│   ├── CartScreen.js       # Shopping cart
│   └── AccountScreen.js    # User profile
├── App.js                  # Main app entry point with navigation
├── package.json            # Dependencies
├── app.json               # Expo configuration
└── README.md              # This file
```

## Screens Overview

### 🏠 Home Screen
- Location selector
- Search bar
- Category navigation
- Featured products grid
- Add to cart functionality

### 🔍 Search Screen
- Real-time product search
- Quick product preview
- Add to cart from search results

### 🛒 Cart Screen
- View all cart items
- Adjust quantities
- Remove items
- Billing breakdown (Subtotal, Tax, Delivery)
- Checkout button

### 👤 Account Screen
- User profile
- Order history
- Favorites
- Addresses
- Payments
- Settings & Support

## API Integration (Future)

To connect this app to a real backend:

1. Replace mock data in screens with API calls using Axios
2. Implement user authentication
3. Add real payment integration
4. Implement location services for delivery tracking

## Customization

### Change App Colors
Edit the color code `#0F6FFF` throughout the screens to your preferred brand color.

### Add More Products
Update the `products` array in `screens/HomeScreen.js` and `allProducts` in `SearchScreen.js`.

### Update Categories
Modify the `categories` array in `screens/HomeScreen.js`.

## Build for Production

### Android
```bash
expo build:android
```

### iOS
```bash
expo build:ios
```

## Future Enhancements

- [ ] Backend API integration
- [ ] User authentication
- [ ] Real-time order tracking
- [ ] Payment gateway integration
- [ ] Push notifications
- [ ] Wishlist feature
- [ ] Ratings & reviews
- [ ] Promo code system
- [ ] Multiple address management
- [ ] Order history

## Contributing

Feel free to fork this project and submit pull requests for any improvements.

## License

MIT License - Feel free to use this project for personal or commercial purposes.

## Support

For issues or questions, please create an issue in the repository.

---

Happy Coding! 🚀
