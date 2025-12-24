# Anatolia Stack

**Anatolia Stack** is a production-ready Go web boilerplate created and maintained by
**Serhan KARAKOÇ**.

It represents a **server-driven, form-based, real-world web architecture** built with Go.

No SPA.
No frontend frameworks.
Just clean, fast and maintainable web applications.

---

## 🧠 Philosophy

Modern web development often favors trends over clarity.

Anatolia Stack is built on a simpler belief:

* Server-side rendering first
* Classic HTML forms
* Session-based authentication
* Minimal JavaScript
* Predictable application flow

This stack is designed for **long-living business software**, not experiments.

---

## ✨ Features

### ⚡ Core Stack

* **Go + Fiber**
* **Server-Side Rendering (SSR)**
* **Classic HTML Form Architecture**
* **Minimal JavaScript (progressive enhancement only)**

---

### 🔐 Authentication & Authorization (Full Auth System)

Authentication is a **first-class citizen** in Anatolia Stack.

* **Session-based authentication**
* **Secure password hashing**
* **CSRF protection**
* **Authentication middleware & guards**
* **Protected routes & access control**

#### Included Auth Flows

* User Login
* User Registration
* Secure Logout
* Password Change
* Forgot Password
* Password Reset via token
* Email-based verification flows (optional / extensible)

---

### 🌐 OAuth Support

* **Google Authentication (OAuth 2.0)**
* Seamless integration with existing session system
* Users can log in via:

  * Email & password
  * Google account
* Designed to support additional providers in the future

---

### 👥 User & Role Management

Anatolia Stack includes a **production-ready user and role system**.

* User management (CRUD)
* Role-based access control (RBAC)
* Multiple roles per user (optional / extensible)
* Authorization handled at:

  * Middleware level
  * Controller/handler level
* Designed for:

  * Admin panels
  * Internal dashboards
  * Multi-role business applications

---

### 🗄 Data & Infrastructure

* **PostgreSQL + GORM**

  * Clean model definitions
  * Migrations & seeds
* **Redis**

  * Session storage
  * Caching layer
* **Environment-based configuration**

  * Development
  * Staging
  * Production

---

### 🚀 Production-Focused Defaults

* Sensible project structure
* Explicit configuration
* Clear separation of concerns
* Built for observability and maintenance
* No hidden magic

---

## 🎯 Who Is This For?

Anatolia Stack is built for developers who:

* Build admin panels and internal tools
* Develop business-critical applications
* Prefer clarity over abstraction
* Value stability and maintainability
* Want full control over their stack
* Do not want to fight frontend complexity for form-based systems

---

## 🤔 Why This Stack?

Most Go projects focus on APIs.

**Anatolia Stack focuses on complete applications.**

* HTML rendered on the server
* Forms handled entirely on the backend
* Authentication treated as a core concern
* User and role management built-in
* Architecture optimized for real users and real traffic

This is how dependable software is built.

---

## 🧭 Vision

Anatolia Stack is not just a boilerplate.

It is an **opinionated foundation** for building serious software with Go.

The goal is not to chase trends,
but to provide a stable and understandable base
that developers can rely on for years.

---

## 👤 Author

**Serhan KARAKOÇ**
Software Developer & Product Builder

Creator of **Anatolia Stack**

> “Simple systems last longer.”

---

## 🤝 Contributing

Anatolia Stack is open to contributions, ideas and discussions.

If you believe in **server-driven web development**
and value simplicity, you are welcome to contribute.

---

## 📄 License

Anatolia Stack is open-source software licensed under the **MIT License**.

---

## ⭐ Support

If Anatolia Stack helps you build better software,
consider giving it a ⭐ on GitHub.
