# 🛡️ AI Safety Incident Dashboard

A responsive and interactive dashboard for viewing, filtering, sorting, and reporting hypothetical AI safety incidents. Built using **vanilla HTML, CSS, and JavaScript**, this project simulates a real-world scenario aligned with AI safety challenges.

## 🚀 Features

- 📋 **View Incidents**: Browse a list of AI safety incidents with title, severity, and reported date.
- 🎯 **Filter by Severity**: Easily filter incidents by severity — Low, Medium, or High.
- 📅 **Sort by Date**: Sort incidents from newest to oldest or vice versa.
- 🔍 **Toggle Details**: Click "View Details" to show or hide the full description of an incident.
- 📝 **Report New Incidents**: Submit new incidents using a responsive form with validation.
- 📱 **Responsive Design**: Fully responsive for mobile, tablet, and desktop screens.

## 🛠️ Setup Instructions

1. Clone or download this repository.
2. Open the `index.html` file directly in your browser.
3. No installation or build steps are required!

## 🧠 Optional Enhancements

To enable **data persistence** between browser sessions using `localStorage`, simply uncomment the following lines at the bottom of `script.js`:

```javascript
// loadFromLocalStorage();
// window.addEventListener('beforeunload', saveToLocalStorage);
