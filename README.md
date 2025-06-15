# 🔐 Spring Security Custom Configuration

This is a **minimal Spring Boot + Spring Security** application designed for testing and learning purposes. It provides a basic setup that **disables CSRF**, **permits all HTTP requests**, and uses the **default Spring login page**. The application is also configured to be **stateless**, making it perfect for API testing via tools like **Postman**.

---

## 📚 Features


- ✅ Stateless session management
- 🔒 Role-based access control (RBAC)
- 🚫 CSRF disabled for easier API testing
- 🗝️ Default login page for browser-based login
- 🌐 Public and protected endpoint access
- 🧪 Postman-friendly setup

---

## 🌐 Endpoints
| Endpoint | Method | Access | Description                             |
| -------- | ------ | ------ | --------------------------------------- |
| `/`      | GET    | Public | Returns welcome message with session ID |

## Test with Postman or browser
  - Visit: http://localhost:8080/
  - You'll see: Welcome to Spring Security Project[SessionID]

### Screenshots

![Screenshot (143)](https://github.com/user-attachments/assets/637dfe17-3efb-4de3-85bd-923eb17f8f6a)

![Screenshot (142)](https://github.com/user-attachments/assets/c03fbfd2-522e-4498-80ad-33aafa22c429)

![Screenshot (144)](https://github.com/user-attachments/assets/2bea276b-5a6a-468a-b07f-927a15b0c5c1)

![Screenshot (145)](https://github.com/user-attachments/assets/9a89f508-c770-4e08-bb9d-ab1156f99167)

![Screenshot (146)](https://github.com/user-attachments/assets/59b6faa7-31b4-4d60-ae8f-8a1ca23be416)

![Screenshot (147)](https://github.com/user-attachments/assets/82e231a4-af2a-4230-9be3-0c8cb6941ab0)



