# ☕ Java Modernization Examples

This folder contains Java-based legacy applications and their modernized counterparts using **Amazon Q Developer** and complementary tooling.

Each project follows a consistent layout to showcase both the **before** (legacy) and **after** (modernized) versions. The goal is to help teams explore how Amazon Q assists in modernizing real-world applications — and where human intervention may still be required.

---

## 📁 Structure

Each subfolder represents a unique modernization use case:

```
java-examples/
├── mini-spring/         # Spring Framework 3.x → Spring Framework 6.x
│   ├── before/          # Legacy codebase (XML-config)
│   ├── after/           # Modernized Spring Framework application
│   └── README.md
│
├── merabazaar/          # Spring Framework 3.x → Spring Framework 6.x
│   ├── before/          # Legacy codebase
│   ├── after/           # Modernized Spring Framework application
│   └── README.md
└── README.md            # You are here
```

---

## 🔄 Modernization Scope

| Project       | Legacy Tech               | Modern Tech                | Transformation Highlights               |
|---------------|---------------------------|----------------------------|-----------------------------------------|
| mini-spring   | Spring Framework 3.x      | Spring Framework 6.x       | XML → annotations                       |
| merabazaar    | Spring Framework 4.x      | Spring Framework 6.x       | Implemented an incomplete DAO class     |

---

## 🧰 Prerequisites

- [Java 8 or 17+](https://www.oracle.com/java/technologies/downloads/)  
- Maven or Gradle (depending on the project)  
- IDE: IntelliJ IDEA, Eclipse, or VS Code  
- (Optional) Amazon Q Developer plugin or CLI  

---

## ▶️ How to Run

Each project includes its own `README.md` with specific setup instructions.

Example for Maven-based Spring Boot app:

```bash
# Navigate to the 'before' version of the project
cd java-examples/mini-spring/before

# Build and run
./mvnw clean install
```

> Legacy (`before/`) projects may require older build tools or server deployment depending on their structure (e.g., WAR files on Tomcat).

---

## 📄 Documentation Files per Project

Each project includes:

- `README.md` – How to build/run the legacy and modern versions
- `MODERNIZATION_NOTES.md` (in `/after`) – Modernization steps, automated vs manual breakdown, known issues

---

## ⚠️ Notes

- Not all transformations are 100% automated.
- This repository aims to reflect **real-world migration complexity**.
- Some "after" projects may include in-progress annotations or TODOs to highlight pending work.

---

## 🤝 Contribute

We welcome contributions! You can:
- Add more Java modernization cases (e.g., Struts → Spring Boot, EJB → REST)
- Improve instructions or transformation strategies
- Submit pull requests or open issues

---