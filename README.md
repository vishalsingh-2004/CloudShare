# CloudShare ☁️

A full-stack file management system that allows users to securely upload, manage, and share files.  
This project demonstrates a modern development workflow, integrating **Spring Boot** and **React** with cloud storage, authentication, and payment gateway support.

## Screenshots

| Landing Page | Dashboard |
| :---: | :---: |
| ![Landing Page](https://github.com/user-attachments/assets/c2d3770f-d731-47a2-84e8-14dbeb5e1a26) | ![Dashboard](https://github.com/user-attachments/assets/c83dbcbe-5c7e-4aa6-a074-d34a514ff866) |

| File View | Payment Details |
| :---: | :---: |
| ![File View](https://github.com/user-attachments/assets/46f8f385-6f6b-4ff5-aecd-788224f6f93c) | ![Payment Details](https://github.com/user-attachments/assets/de12df42-fb7b-4b02-ad2b-95d520128233) |

| Signup | Subscription Plan |
| :---: | :---: |
| ![Signup](https://github.com/user-attachments/assets/ef0a956f-3056-491e-b9af-b7b957effbe7) | ![Subscription Plan](https://github.com/user-attachments/assets/f6021059-0f84-435b-9122-5d16f9ee960d) |



## Key Features

* **File Management:** Upload, view, download, and delete files with ease.
* **Access Control:** Toggle files between **public** and **private** modes.
* **File Sharing:** Generate unique public links for sharing.
* **User Authentication:** Secure login and signup powered by **Clerk**.
* **Responsive UI:** Built with **Tailwind CSS** and **Lucide Icons** for a modern experience.
* **Multiple Views:** Switch between grid and list layouts.
* **Payment Integration:** Razorpay integration for premium features.

## 🛠️ Tech Stack

![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![TailwindCSS](https://img.shields.io/badge/TailwindCSS-3-38B2AC?style=for-the-badge&logo=tailwindcss&logoColor=white)
![Lucide Icons](https://img.shields.io/badge/Lucide-Icons-000000?style=for-the-badge&logo=lucide&logoColor=white)
![Clerk](https://img.shields.io/badge/Clerk-Auth-3B82F6?style=for-the-badge&logo=clerk&logoColor=white)

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.0-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

![Razorpay](https://img.shields.io/badge/Razorpay-Payments-02042B?style=for-the-badge&logo=razorpay&logoColor=00AEEF)

---

## 📖 What I Learned  

* Full-stack integration between **React & Spring Boot**  
* Implementing **authentication** & user-based file access  
* Building **responsive UIs** with Tailwind CSS  
* **Payment gateway integration** with Razorpay  
* Writing **clean, reusable React components**  

---

## Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

* Java JDK 17+
* Node.js and npm (or yarn)
* MongoDB Server
* Maven
* Clerk account and API keys
* Razorpay account and API keys

### Backend Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/cloud-share.git
    cd cloud-share/backend
    ```
2. Configure your `application.properties` file:
    * MongoDB connection details
    * Clerk Auth credentials
    * Razorpay API keys
3. Run the Spring Boot application:
    ```bash
    ./mvnw spring-boot:run
    ```

### Frontend Setup

1. Navigate to the `client` directory:
    ```bash
    cd client
    ```
2. Install dependencies:
    ```bash
    npm install
    ```
3. Start the React application:
    ```bash
    npm run dev
    ```

The application should now be running on `http://localhost:5173`.

## Author

* Vishal Singh - [LinkedIn](https://www.linkedin.com/in/vishal-singh-81988928b/) - [GitHub](https://github.com/vishalsingh-2004)

Feel free to connect with me if you have any questions or feedback!

