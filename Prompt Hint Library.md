# Prompt Hint Library - Reusable Amazon Q Hints for Custom Modernizations

## 1. Controller Modernization
```csharp
// Q Hint: Convert this ASP.NET MVC controller to ASP.NET Core Web API.
// Use attribute routing, constructor injection, and IActionResult return types.
// Assume the services are registered in DI and follow async pattern.
```

---

## 2. Dependency Injection
```csharp
// Q Hint: Replace direct instantiation with constructor-based dependency injection.
// Assume ILogger<T> and IStudentService are available via DI.
```

---

## 3. Data Access – ADO.NET to EF Core
```csharp
// Q Hint: Replace SqlConnection and SqlCommand usage with EF Core DbContext.
// Assume DbContext has a Students DbSet with properties Id, Name, Age.
```

---

## 4. Synchronous to Asynchronous
```csharp
// Q Hint: Convert all synchronous DB calls to async/await using EF Core.
// Use Task-based method signatures.
```

---

## 5. HttpContext / Session Modernization
```csharp
// Q Hint: Replace HttpContext.Current usage with IHttpContextAccessor.
// Refactor to support scoped services and ASP.NET Core request lifecycle.
```

---

## 6. Configuration
```csharp
// Q Hint: Replace ConfigurationManager.AppSettings with IConfiguration and strongly-typed settings classes.
// Assume config values are loaded from appsettings.json.
```

---

## 7. Logging
```csharp
// Q Hint: Replace System.Diagnostics.Trace or Console.WriteLine with ILogger<T> from Microsoft.Extensions.Logging.
```

---

## 8. Routing & API Attributes
```csharp
// Q Hint: Add [ApiController] and [Route("api/[controller]")] to modernize routing conventions.
```

---

## 9. Startup & Middleware
```csharp
// Q Hint: Remove Global.asax and replace with ASP.NET Core middleware-based startup pattern.
// Assume a Program.cs with WebApplication.CreateBuilder().
```

---

## 10. Validation
```csharp
// Q Hint: Replace manual model validation with Data Annotations and [ApiController]-enabled model binding.
```