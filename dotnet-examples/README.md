# 🧩 .NET Modernization Examples

This folder showcases legacy .NET Framework applications and their modernized versions using **Amazon Q Developer** and related modernization techniques.

Each project follows a standardized structure that illustrates the **before** (legacy) and **after** (modernized) states, making it easier to understand the scope of automation, tooling used, and manual interventions.

---

## 📁 Structure

Each subfolder represents a distinct .NET modernization example:

```
dotnet-examples/
├── asp.net-mvc5-architecture/   # Classic MVC 5 web app → ASP.NET Core
│   ├── before/                  # .NET Framework 4.5+ legacy app
│   ├── after/                   # ASP.NET Core MVC modernized version
│   └── README.md
│
├── wcf-sample-project/          # WCF SOAP service → CoreWCF Services
│   ├── before/                  # .NET Framework WCF implementation
│   ├── after/                   # .NET CoreWCF Services
│   └── README.md
|
└── README.md                    # You are here
```

---

## 🔄 Modernization Scope

| Project                   | Legacy Tech            | Modern Tech                 | Transformation Highlights                            |
|------------------------   |------------------------|-----------------------------|------------------------------------------------------|
| asp-net-mvc5-architecture | ASP.NET MVC 5          | ASP.NET Core MVC            | Controllers, DI, project format upgrade              |
| wcf-sample-project        | WCF (SOAP)             | CoreWCF Services            | Protocol shift, REST endpoints, simplified hosting   |

---

## 🧰 Prerequisites

- [.NET SDK 8.0](https://dotnet.microsoft.com/en-us/download)
- Visual Studio 2022+ or VS Code
- Amazon Q Developer plugin or CLI (optional)

---

## ▶️ How to Run

Each project includes a `README.md` with specific instructions. Typical steps include:

```bash
# Build and run legacy project (Framework)
cd dotnet-examples/asp-net-mvc5-architecture/before
# Open in Visual Studio and run via IIS Express

# Run modernized project (ASP.NET Core)
cd ../../after
dotnet build
dotnet run
```

> Legacy (`before/`) projects may require older build tools or server deployment depending on their structure (e.g., IIS Express).

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

## 🤝 Contributions

Feel free to:

- Add more .NET examples (.NET MAUI, WinForms to Blazor, etc.)
- Suggest improvements to modernization workflows
- Submit fixes or enhancements via pull requests

---
