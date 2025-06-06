# MyDashboard - Product Management System

A React-based product management dashboard with user authentication, theme switching, and CRUD operations for products.

## Features

- User Registration and Login
- Product Management (Add, Edit, Delete)
- Dark/Light Theme Toggle
- Responsive Material-UI Design
- Form Validation
- Protected Routes
- Total Inventory Value Calculation

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd mydashboard
```

2. Install dependencies:
```bash
npm install
```

## Running the Application

1. Start the development server:
```bash
npm start
```

2. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Usage

1. Register a new account using the registration form
2. Log in with your credentials
3. Access the dashboard to manage products:
   - View product list
   - Add new products
   - Edit existing products
   - Delete products
   - Toggle between dark and light themes

## Technologies Used

- React
- TypeScript
- Redux Toolkit
- Material-UI
- React Router
- Formik & Yup
- UUID

## Project Structure

```
src/
  ├── components/
  │   ├── auth/
  │   │   ├── Login.tsx
  │   │   └── Register.tsx
  │   └── dashboard/
  │       ├── Dashboard.tsx
  │       └── ProductForm.tsx
  ├── store/
  │   ├── authSlice.ts
  │   ├── productSlice.ts
  │   └── store.ts
  ├── types/
  │   ├── auth.ts
  │   └── product.ts
  ├── theme/
  │   └── theme.ts
  ├── App.tsx
  └── index.tsx
```

## Default Credentials

For testing purposes, you can register a new account or use any email/password combination as the authentication is currently mocked.

## License

MIT
