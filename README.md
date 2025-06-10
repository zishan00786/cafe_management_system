# cafe_management_system



A simple full-stack web application that allows users to view the cafe menu, place orders, and receive the bill. Built using **Java (Spring Boot)** for backend, **MySQL** for the database, and **HTML/CSS/JavaScript** for the frontend.

---

## 📁 Project Structure
/cafe-management-system
│
├── backend/ # Spring Boot backend
├── frontend/ # HTML/JS frontend
├── screenshot.png # Preview image
└── README.md # Project documentation


---

## 🔧 Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: Java, Spring Boot, Spring Data JPA
- **Database**: MySQL
- **Tools**: IntelliJ IDEA, MySQL Workbench, Postman, GitHub

---

## 🚀 How to Run the Project

### 📦 Backend (Spring Boot)

1. Open the `/backend` folder in IntelliJ IDEA.
2. Configure `application.properties` with your MySQL credentials:

```properties
spring.datasource.url=jdbc:mysql://localhost:3306/cafedb
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update

Run CafeBackendApplication.java from the main class.

🌐 Frontend (HTML/JavaScript)
Open /frontend/index.html in your browser.

You should see the menu, and you can place orders.

📡 API Endpoints
GET /api/menu – Retrieve list of menu items

POST /api/order – Submit selected items and receive total price

📸 Screenshot
A preview of the system:


✅ Example Request/Response
🟢 Request (POST /api/order)

{
  "items": [1, 2]
}
🔵 Response

{
  "orderId": 101,
  "items": [
    {"name": "Coffee", "price": 50},
    {"name": "Tea", "price": 30}
  ],
  "total": 80
}
👨‍💻 Team
 Name – kamran Alam

Teammate Name – Md Zishan
                dev kaushik


Core Feature Implementation 

Users can:

View cafe menu (GET /api/menu)

Select items

Place order (POST /api/order)

Get total bill with item list

🛡️ Error Handling & Robustness ✅

Frontend alerts if no item is selected

Backend checks for:

Empty item list

Invalid IDs

Graceful error messages are shown to users

🔗 Integration of Components ✅

Frontend communicates with backend using fetch()

Backend responds with JSON, properly handled on UI

All components work together smoothly

⚙️ Event Handling and Processing ✅

JavaScript listens for order submission

Optimized for responsiveness and performance

✔️ Data Validation ✅

Frontend: Validates selection before allowing submission

Backend: Validates item existence before calculating total

📐 Code Quality & Innovation ✅

Code is modular and well-commented

Spring Boot backend uses:

Controller layer

Model layer

Repository layer

Extra: You can optionally add admin feature or item search (bonus)

📄 Project Documentation ✅

Full README.md with:

Setup instructions for frontend and backend

API details and usage

Sample request and response

Real/placeholder screenshots

All files are properly structured and documented

👨‍💻 Developer

Md Zishan

kamran alam

dev kaushik




