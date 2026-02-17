# Medical Prescription Web Application

A simple web application to create and print medical prescriptions, designed for educational purposes. Built using HTML, CSS, JavaScript (Vanilla JS and jQuery) and Bootstrap 5.

---

## 🔹 Features

- Fill in patient and doctor information using a web form.
- Automatic generation of the prescription on a separate page (`Receituario.html`).
- Direct printing from the browser using a print button.
- Input validation for numeric fields (phone, CRM, CNES) using jQuery.
- Responsive layout using Bootstrap.
- Date formatting (dd/mm/yyyy) for the prescription issuance date.

---

## 💻 How It Works

1. The user fills out the form on `index.html`.
2. Form data is passed to `Receituario.html` via URL query parameters.
3. `imprimir.js` (or the inline JavaScript) reads the URL parameters using `URLSearchParams`.
4. The script dynamically inserts the data into the `<div class="Receituario">` container using template literals.
5. Clicking the print button (`#bi`) calls `window.print()` to print the prescription.

This allows a seamless flow from data input to a printable prescription.

---

## 💻 Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla JS)
- jQuery (for input validation)
- Bootstrap 5 (layout and styling)
- Organized folder structure (`assets`) for scripts, styles, and images.

---

## 🗂 Project Structure

