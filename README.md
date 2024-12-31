# Online Restaurant Ordering System with Dietary Recommendations

## Overview
The **Online Restaurant Ordering System with Dietary Recommendations** is a web-based platform designed to enhance the food ordering experience by integrating dietary customization. This system provides tailored menu recommendations based on individual dietary preferences, such as vegan, gluten-free, or lactose-free, while offering a robust admin dashboard for restaurant management.

---

## Features
### Customer Portal
- **Personalized Recommendations**: Filter menus based on dietary preferences (e.g., vegan, gluten-free).
- **Order Management**: Add items to a cart and place orders with ease.
- **User Profile**: Store dietary preferences and order history for a personalized experience.

### Admin Dashboard
- **Menu Management**: Add, update, and delete menu items.
- **Order Tracking**: Monitor real-time orders and statuses.
- **Sales Insights**: Access reports and analytics to track performance.

### Additional Features
- **Secure Transactions**: Integrated secure payment gateway.
- **Mobile-Friendly Design**: Fully responsive for use on smartphones, tablets, and desktops.
- **Notifications**: Real-time updates for customers and administrators.

---

## Technology Stack
### Frontend
- **HTML** and **CSS**: For a responsive and user-friendly interface.
- **JavaScript**: Adds interactivity to the UI.

### Backend
- **Python Flask**: Handles server-side logic and API development.

### Database
- **MySQL**: Manages structured data storage for users, orders, and menu items.

### Tools
- **VS Code**: Preferred IDE for development.
- **GitHub**: Version control and collaboration.

---

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/online-restaurant-ordering.git
   ```

2. Navigate to the project directory:
   ```bash
   cd online-restaurant-ordering
   ```

3. Set up the virtual environment:
   ```bash
   python -m venv env
   source env/bin/activate  # On Windows: env\Scripts\activate
   ```

4. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

5. Set up the database:
   - Import the provided `schema.sql` file into MySQL.
   - Update the database configuration in `config.py`.

6. Run the application:
   ```bash
   flask run
   ```

7. Access the application in your browser:
   - Customer Portal: `http://localhost:5000`
   - Admin Dashboard: `http://localhost:5000/admin`

---

## Database Schema
### Tables
- **Users**: Stores customer details and preferences.
- **Menu**: Contains menu items with dietary classifications.
- **Orders**: Tracks orders placed by customers.
- **Cart**: Manages temporary order details before placement.
- **Admin Logs**: Records administrative actions.

### Relationships
- Users and Orders: One-to-many.
- Users and Cart: One-to-many.
- Menu and Orders: Many-to-many.

---

## Usage
### For Customers
1. Sign up and create a profile, including dietary preferences.
2. Browse the menu and filter items based on preferences.
3. Add items to your cart and place an order.
4. Track your order status in real-time.

### For Admins
1. Log in to the admin dashboard.
2. Manage menu items and track active orders.
3. View analytics and reports for business insights.

---

## Future Enhancements
1. **AI-Driven Recommendations**: Use machine learning to refine menu suggestions.
2. **Mobile Application**: Develop native apps for Android and iOS.
3. **Wearable Integration**: Sync with health trackers for personalized dietary insights.

---

## Contributing
We welcome contributions to this project! To get started:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add feature-name"
   ```
4. Push to your branch:
   ```bash
   git push origin feature-name
   ```
5. Submit a pull request.

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Contact
For questions or feedback, please contact:
- **Email**: 1ms22cs039@msrit.edu
- **GitHub**: [your-username](https://github.com/bpdeepak)
