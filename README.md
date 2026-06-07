# dotnet-api-best-practices
A collection of best practices for building robust, scalable, secure, and maintainable .NET APIs. Includes patterns for validation, error handling, logging, versioning, pagination, DTO mapping, testing, and architecture guidance.

# .NET API Best Practices

A curated collection of best practices, patterns, and examples for building robust, scalable, and maintainable APIs using .NET 8 and C#.  
This repository is designed to help developers write clean, consistent, and production‑ready APIs.

---

## 🚀 Goals of This Repository

- Provide real-world API patterns used in enterprise systems  
- Demonstrate clean architecture and SOLID principles  
- Offer reusable code samples for common API scenarios  
- Help developers avoid common pitfalls in API design  
- Serve as a reference for interviews, onboarding, and team standards  

---

## 📁 Repository Structure

****
src/                → Best practice implementations
samples/            → Small runnable examples
docs/               → Deep-dive explanations
tests/              → Unit + integration tests


---

## 📌 Included Best Practices

### **1. API Versioning**
- URL versioning  
- Header versioning  
- Minimal API versioning  
- Deprecation strategy  

### **2. Global Error Handling**
- Centralized exception middleware  
- ProblemDetails response format  
- Custom error codes  
- Logging correlation IDs  

### **3. Validation**
- FluentValidation  
- Model binding validation  
- Request/response validation  
- Validation filters  

### **4. Logging & Monitoring**
- Serilog structured logging  
- Request/response logging  
- Correlation ID middleware  
- Application Insights integration  

### **5. Pagination, Filtering & Sorting**
- Standardized pagination response  
- Query parameter filtering  
- Dynamic sorting  
- LINQ extensions  

### **6. DTOs & Mapping**
- AutoMapper profiles  
- Avoiding over-posting  
- Request/response separation  
- Domain vs API models  

### **7. Authentication & Authorization**
- JWT authentication  
- Role-based authorization  
- Policy-based authorization  
- Minimal API auth patterns  

### **8. Clean Architecture Principles**
- Domain layer  
- Application layer  
- Infrastructure layer  
- API layer  
- Dependency inversion  

### **9. SOLID Principles in API Design**
- Single Responsibility in controllers  
- Interface segregation for services  
- Dependency injection best practices  

### **10. Testing**
- Unit tests with xUnit  
- Integration tests with TestServer  
- Mocking with Moq  
- API contract tests  

---

## 🧪 Running the Samples

Each folder under `/samples` contains a small runnable project demonstrating a specific best practice.

cd samples/MinimalApiExample
dotnet run


---

## 🤝 Contributions

This repo is designed to help the community.  
Feel free to open issues, suggest improvements, or submit PRs.

---

## ⭐ Support

If you find this useful, please ⭐ star the repository — it helps others discover it.

---

## 📬 Contact

Created by **Luqman Cheema**  
Senior .NET Developer | API Specialist | Cloud‑Ready Engineer


