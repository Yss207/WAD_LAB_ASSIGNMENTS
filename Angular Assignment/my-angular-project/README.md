# 📝 Angular Assignment – User Registration, Login & Profile

This Angular application was created as part of a college assignment with the objective to:

> ✅ Register Users  
> ✅ Allow Users to Login  
> ✅ Display Logged-in User Data in a Profile Component  

The entire app is built using Angular and handles user data using **Browser LocalStorage** — no backend involved.

---

## 🚀 Features

- 🧾 **User Registration Form**
- 🔐 **User Login with Student ID and Password**
- 👤 **Profile Page Showing User Details**
- 🚪 **Logout Functionality**
- 🌐 **Angular Routing with Navigation**

---

## 🧠 Angular Concepts Used

- ✅ **Components** (`RegisterComponent`, `LoginComponent`, `ProfileComponent`)
- ✅ **Modules** (`AppModule`, `AppRoutingModule`)
- ✅ **Routing & Navigation** (`<router-outlet>`, `routerLink`)
- ✅ **Two-Way Data Binding** (`[(ngModel)]`)
- ✅ **Property Binding** (`[disabled]`, `[value]`, etc.)
- ✅ **Event Binding** (`(click)`)
- ✅ **Directives** (`*ngIf`, `*ngFor`)
- ✅ **LocalStorage for persistent user session**
- ✅ **Angular CLI** for generating and serving the app

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version **19.2.3**.

---

## 📂Project Structure
    ```bash
    src/
    ├── app/
    │   ├── components/
    │   │   ├── register/
    │   │   ├── login/
    │   │   └── profile/
    │   ├── app-routing.module.ts
    │   └── app.module.ts
    ├── assets/
    ├── index.html
    └── main.ts
    ```

---

## 🛠️ How to Run Locally

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/angular-user-auth-assignment.git
   ```

2. Navigate into the project directory:
   ```bash
   cd angular-user-auth-assignment
   ```

3. Install all the required dependencies:
    ```bash
    npm install
    ```

4. Run the development server:
    ```bash
    ng serve
    ```

Open browser and visit http://localhost:4200



