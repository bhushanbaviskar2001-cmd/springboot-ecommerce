# SpringBoot-Ecommerce

A full-stack E-Commerce web application featuring a **React.js** frontend (built with Vite), a **Spring Boot** backend, and integrated **MySQL** database. The application delivers a modern, responsive shopping experience for users and is an excellent foundation for further development, learning, or portfolio showcase[attached_file:1].

## Features

- Responsive design for desktop and mobile[attached_file:1]
- Product listing, details, search, and CRUD operations
- User authentication and authorization
- Shopping cart management, order placement
- RESTful API endpoints using Spring Boot
- Hot Module Replacement (HMR) and fast dev cycle with Vite[attached_file:1]
- Modular architecture (frontend/backend separation)

## Tech Stack

| Technology   | Purpose                |
|--------------|------------------------|
| React.js     | Frontend framework[attached_file:1] |
| Vite         | Frontend tooling (HMR)[attached_file:1] |
| Spring Boot  | Backend API/server[attached_file:1] |
| MySQL        | Database[attached_file:1] |
| JavaScript   | Frontend logic[attached_file:1] |
| Java         | Backend logic[attached_file:1] |
| CSS          | Styling[attached_file:1] |
| HTML         | UI structure[attached_file:1] |

## Getting Started

### Prerequisites

- Node.js (v16+)
- npm or yarn
- Java (17+)
- Maven (for backend)
- MySQL server

### Backend: Spring Boot Setup

1. **Database Initialization**
   - Create a MySQL database (e.g. `ecomdb`)
   - Edit `application.properties` with your credentials:
     ```
     spring.datasource.url=jdbc:mysql://localhost:3306/ecomdb
     spring.datasource.username=your_db_user
     spring.datasource.password=your_db_password
     spring.jpa.hibernate.ddl-auto=update
     ```
2. **Build and Run**
   - In the backend directory, run:
     ```
     mvn spring-boot:run
     ```

### Frontend: React + Vite Setup

1. **Install dependencies**
   - In the frontend directory:
     ```
     npm install
     ```
2. **Run development server**
   - Start the frontend:
     ```
     npm run dev
     ```
   - Visit: `http://localhost:5173`
3. **API Connection**
   - Make sure frontend API endpoints match backend URL, e.g. `http://localhost:8080`

## Project Structure

springboot-ecommerce/
├── backend/ # Spring Boot REST API
│ └── ... # Controllers, services, models, etc.
├── frontend/ # React.js + Vite frontend
│ └── ... # Components, pages, assets, etc.
└── README.md # Project documentation


## Contributing

Contributions are welcome! Fork this repo and submit pull requests for improvements.

## License

Provided for educational and demonstration purposes only.

