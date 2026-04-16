# Deployment of Full-Stack Application (Spring Boot + React)

## 👤 Student Details

**Name:** Rebaka Meda
**Registration Number:2400032563

---

## 🎯 Aim

To deploy a production-ready full-stack application using React for the frontend and Spring Boot for the backend, and to ensure proper integration between them.

---

## 🧰 Prerequisites

* Basic knowledge of Spring Boot
* Understanding of React build process
* Basic knowledge of deployment concepts

---

## ⚙️ Tools & Technologies Used

* React.js
* Spring Boot
* Maven
* Eclipse IDE
* VS Code

---

## 🚀 Procedure

### 1. React Frontend Build

* Created a React application using `create-react-app`
* Installed dependencies using:

  ```
  npm install
  ```
* Generated production build:

  ```
  npm run build
  ```
* A `build/` folder was created containing optimized static files

---

### 2. Spring Boot Backend Setup

* Created Spring Boot project using Spring Starter (Eclipse)
* Added dependency:

  * Spring Web

---

### 3. REST API Creation

Created a controller:

```java
@RestController
public class TestController {

    @GetMapping("/api/test")
    public String test() {
        return "Backend is working!";
    }
}
```

---

### 4. Integration of Frontend and Backend

* Copied all files from:

  ```
  frontend/build/
  ```
* Pasted into:

  ```
  src/main/resources/static/
  ```
* This allowed Spring Boot to serve React frontend

---

### 5. Running the Application

* Ran Spring Boot application
* Server started on:

  ```
  http://localhost:8080
  ```

---

### 6. Testing

#### API Test:

```
http://localhost:8080/api/test
```

✔ Output: Backend is working!

#### Full Application:

```
http://localhost:8080
```

✔ React frontend loaded successfully
✔ Backend data displayed on UI

---

## 📸 Output

* React build successful
* Spring Boot server running
* API response verified
* Full-stack application successfully deployed

---

## ✅ Result

The full-stack application was successfully deployed.
The React frontend and Spring Boot backend were integrated and tested successfully.

---

## 📌 Conclusion

This experiment demonstrates how to deploy a full-stack application by combining React and Spring Boot, ensuring proper communication between frontend and backend in a production-like setup.

---
