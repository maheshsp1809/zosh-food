# ZoshFood - Online Food Delivery Platform

**ZoshFood** is a full-stack online food delivery platform built with Java (Spring Boot) for the backend and React for the frontend. The application provides seamless user experiences for both customers and restaurant owners, including secure authentication, menu management, order placement, and payment processing.

## 🚀 Features

- **User Authentication**: Secure login and registration for customers and restaurant owners using JWT.
- **Role-Based Access Control**: Different functionalities based on user roles (Customer, Restaurant Owner).
- **Restaurant Management**: Owners can manage menus, add new food items, categorize food, and host events.
- **Order Management**: Customers can browse restaurants, place orders, and track them; owners can update order statuses.
- **Payment Integration**: Stripe payment gateway integration for secure and efficient transactions.
- **Email Notifications**: Automated email notifications using Nodemailer and Spring Boot Mail.
- **Responsive Design**: Fully responsive UI built with Tailwind CSS and MUI.

## 🛠️ Technology Stack

### Frontend:

- **React.js**
- **Tailwind CSS**
- **MUI (Material-UI)**
- **Redux Toolkit** (State Management)
- **Axios** (API requests)

### Backend:

- **Spring Boot**
- **Spring Security**
- **JWT Authentication**
- **MySQL** (Database)
- **Spring Mail** (Email service)
- **Stripe API** (Payment gateway)

### Tools:

- **IntelliJ IDEA** (Backend development)
- **VS Code** (Frontend development)

## 📂 Project Structure

```plaintext
ZoshFood/
├── backend/
│   ├── src/
│   │   ├── main/
│   │   ├── resources/
│   │   ├── java/
│   │   └── application.properties
│   └── pom.xml
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── redux/
│   │   ├── services/
│   │   └── App.js
│   ├── package.json
│   └── tailwind.config.js
└── README.md
```

## 🚀 Getting Started

### Prerequisites

- **Node.js** and **npm/yarn**
- **Java JDK 8+**
- **MySQL Database**

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/zoshfood.git
   ```
2. **Backend Setup:**

   - Navigate to the `backend` directory.
   - Configure the `application.properties` file with your MySQL database credentials.
   - Build and run the Spring Boot application:
     ```bash
     mvn clean install
     mvn spring-boot:run
     ```

3. **Frontend Setup:**
   - Navigate to the `frontend` directory.
   - Install the dependencies:
     ```bash
     npm install
     ```
   - Start the React development server:
     ```bash
     npm start
     ```

## 🔧 Usage

### Customer:

1. **Browse Restaurants:** View all available restaurants.
2. **Add to Cart:** Select food items and add them to the cart.
3. **Place Order:** Add delivery address and proceed to payment.
4. **Order Tracking:** Track your order status.

### Restaurant Owner:

1. **Manage Menu:** Add, edit, or remove food items.
2. **View Orders:** Check incoming orders and update their status.
3. **Host Events:** Create and manage restaurant events.

## 🚀 Deployment

### Backend:

1. Build the Spring Boot application:
   ```bash
   mvn clean package
   ```
2. Deploy the `.jar` file on a server (e.g., AWS, Heroku).

### Frontend:

1. Build the React application:
   ```bash
   npm run build
   ```
2. Deploy the `build` folder on a web server (e.g., Netlify, Vercel).

## 🛡️ Security

- **Authentication:** JWT for secure API access.
- **Encryption:** Passwords are hashed using bcrypt.
- **Data Validation:** Backend input validation using Hibernate Validator.

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🤝 Contributing

Contributions are welcome! Please read the [CONTRIBUTING.md](CONTRIBUTING.md) for more information on how to get started.

## 💬 Contact

For any inquiries or questions, feel free to reach out:

- **Email:** maheshsp1809@gmail.com

---
