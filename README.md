# Deployment of Full-Stack Application (Spring Boot + React)

## 👤 Student Details

**Name:** Rebekah Meda
**Registration Number:** 2400032563

---

## 🎯 Aim

To deploy a production-ready full-stack application using React and Spring Boot.

---

## 🧰 Tools Used

* React.js
* Spring Boot
* Eclipse
* VS Code
* Maven

---

## 🚀 Procedure with Screenshots

---

### 🔹 Step 1: React Build

Command used:

```
npm run build
```

📸 Screenshot:
![React Build](screenshots/react-build-successful.png)

---

### 🔹 Step 2: Spring Boot Project Creation

📸 Screenshot:
![Spring Project](screenshots/spring-project.png)

---

### 🔹 Step 3: Controller Code

```java
@RestController
public class TestController {
    @GetMapping("/api/test")
    public String test() {
        return "Backend is working!";
    }
}
```

📸 Screenshot:
![Controller](screenshots/controller.png)

---

### 🔹 Step 4: Backend Running

📸 Screenshot:
![Backend Running](screenshots/backend-running.png)

---

### 🔹 Step 5: API Output

URL:

```
http://localhost:8080/api/test
```

📸 Screenshot:
![API Output](screenshots/API-response-verified.png)

---

### 🔹 Step 6: Static Folder Integration

📸 Screenshot:
![Static Folder](screenshots/static-folder-integration.png)

---

### 🔹 Step 7: Final Output

URL:

```
http://localhost:8080
```

📸 Screenshot:
![Final Output](screenshots/full-stack-applicatio-successfully-deployed.png)

---

## ✅ Result

The full-stack application was successfully deployed and tested.

---

## 📌 Conclusion

Frontend and backend were integrated successfully using Spring Boot static deployment.

---
