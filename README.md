# Spring Boot – Proxies, Interceptors, Caching & Reflection 

A hands-on Spring Boot project exploring core runtime concepts including JDK & CGLIB proxies, method interception, caching, and Java Reflection API.

---

## Covered Concepts

### 🔁 Proxies
- Implemented both **JDK Dynamic Proxies** and **CGLIB Proxies**
- Understood Spring's proxy selection rules (interfaces vs concrete classes)

### 🕵️ Method Interception
- Used `InvocationHandler` (JDK) and `MethodInterceptor` (CGLIB)
- Logged method execution, arguments, and return values

### 🔍 Reflection API
- Invoked methods dynamically using `Class.forName()`, `Method.invoke()`, etc.
- Explored dynamic access to services and properties

### 🧊 Caching with `@Cacheable`
- Configured Spring's in-memory caching
- Observed self-invocation issues and proxy-based caching limits

---

## Tech Stack

- Java 17
- Spring Boot 3.x
- Gradle
- Spring Context, Caching
- JDK Proxy API, CGLIB
- IntelliJ IDEA

---

## 📂 Structure Overview

```bash
src/
├── proxies/           # JDK and CGLIB proxy demos
├── interceptors/      # Custom method interceptors
├── cache/             # @Cacheable use cases
└── reflection/        # Reflection-based method calls
