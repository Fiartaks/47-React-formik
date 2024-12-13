# 🔑 Login Application with formik

## 📖 Project Overview
🌍 This Login Application, built with **Formik**, provides users with a simple interface to input their email, age, password, and confirm their password. The application utilizes Formik for form handling and Yup for validation, ensuring a smooth user experience and data integrity.

## 📸 Screenshots 📸

![f.gif](https://github.com/Fiartaks/47-React-formik/blob/main/formik/public/f.gif)


## 💻 What’s in the Project?
- 🌟 **Main Component (App.js)**: The main entry point that renders the LoginPage component.  
- 📝 **Input Fields (InputField.js)**: A reusable component for rendering individual input fields along with error handling.  
- 🔗 **Form Schema (schema.js)**: Defines validation rules for input fields using Yup.  
- 💻 **Login Page Component (LoginPage.js)**: Contains the form for user input and handles form submission using Formik.  
- 📦 **Constants (constant.js)**: Holds the definitions and specifications for input fields.  
- 🎨 **Styling (index.css)**: SCSS and CSS styling for the application, ensuring a sleek appearance.

## 🏗️ MVC Characteristics

### 1. Model
- **Data Representation**: The `schema` determines the structure and requirements for user input (including fields like email, age, password, and confirmPassword).
- **Validation Logic**: The validation schema is structured to ensure that user inputs meet the specified criteria.

### 2. View
- **User Interface**: The `LoginPage` component provides the UI for users to log in. It utilizes the `InputField` component to render individual input fields dynamically.
- **Styling**: Uses CSS for styling components, including error messages and form validations.

### 3. Controller
- **Business Logic**: The `LoginPage` component handles user actions, validates input through Formik, and displays errors when necessary.
- **Form Submission**: The form's submission and validation are handled within the component, clarifying the flow of data.

## 🛠️ What Has Been Done in the Project?
- 🔄 Implemented form handling using Formik for managing state and errors.  
- ✅ Integrated validation mechanisms using Yup to enforce rules on input fields.  
- 📈 Equipped the interface for a responsive and user-friendly experience.

## 📦 Libraries
- 📘 React  
- 📦 Formik  
- 📜 Yup  
- 🎨 SCSS  

