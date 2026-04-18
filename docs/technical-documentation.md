# Technical Documentation – Assignment 3 

## 1. Project Overview

This project is a responsive personal portfolio website developed using HTML, CSS, and JavaScript.

In Assignment 3, the project was enhanced by adding advanced functionality, dynamic features, and improved user interaction. The goal was to demonstrate the use of external APIs, complex logic, and better state management.

---

## 2. Project Structure

The project follows a clean and organized structure:

- **HTML** defines the structure and content of the website  
- **CSS** handles styling, layout, and responsiveness  
- **JavaScript** manages interactivity and dynamic behavior  
- **Assets** folder contains images and media  
- **Docs** folder includes documentation files  

This structure improves maintainability and scalability.

---

## 3. Technologies Used

- HTML5  
- CSS3  
  - Flexbox (layout alignment)  
  - CSS Grid (project cards layout)  
  - Media Queries (responsive design)  
- JavaScript  
  - DOM manipulation  
  - Event handling  
  - Async/Await (API requests)  
- Responsive Design principles  

---

## 4. Responsive Design Implementation

The website adapts to different screen sizes:

- Desktop  
- Tablet  
- Mobile  

Techniques used:

- Flexbox for layout alignment (About, Contact sections)  
- CSS Grid for organizing project cards  
- Media queries for adjusting layout on smaller screens  
- Max-width containers for better readability  

Testing was performed using browser resizing and DevTools.

---

## 5. State Management (Dark/Light Mode)

Theme switching is implemented using JavaScript:

- A button toggles the `light-mode` class on the `<body>`  
- CSS overrides define light mode styling  
- `localStorage` stores the user's theme preference  
- The saved theme is applied on page load  

This ensures a consistent user experience.

---

## 6. Interactive Features

### Show More / Show Less

- Each project includes:
  - A short description (default)
  - A full description (hidden)
- A button toggles visibility using JavaScript  
- Button text updates dynamically  

This keeps the layout clean and interactive.

---

## 7. Contact Form and Validation

The contact section includes:

- Name input  
- Email input (validated by browser)  
- Message textarea  
- Submit button  

Functionality:

- Required fields enforced using HTML validation  
- JavaScript handles submission  
- `event.preventDefault()` prevents page reload  
- Success message is displayed  
- Form resets after submission  

---

## 8. API Integration — Advice Feature

An external API was used to display dynamic content.

### How it works

- A request is sent using `fetch`  
- The response is converted to JSON  
- Advice text is extracted and displayed in the UI  

### Error Handling

- If the API fails, a fallback message is shown  
- Prevents application crashes  

This demonstrates external API integration and dynamic updates.

---

## 9. Countdown Timer (Complex Logic)

A graduation countdown timer was implemented.

### How it works

- A future date is defined using JavaScript  
- Current time is retrieved continuously  
- The difference is calculated  
- Converted into:
  - Days
  - Hours
  - Minutes
  - Seconds  
- Updated every second using `setInterval`

### Logic

- Mathematical calculations convert milliseconds  
- Condition checks when countdown ends  

This demonstrates advanced JavaScript logic.

---

## 10. Performance Optimization

Basic performance improvements were applied:

- Images use `loading="lazy"` for faster loading  
- Unused code was removed  
- Efficient CSS properties were used  
- DOM access was optimized in JavaScript  

These steps improve loading speed and efficiency.

---

## 11. UI/UX Considerations

The design focuses on usability:

- Clear layout and navigation  
- Consistent spacing and alignment  
- Interactive elements (buttons, API, countdown)  
- Real-time updates improve engagement  
- Responsive design ensures smooth experience  

---

## 12. Testing & Validation

The project was tested to ensure functionality:

- Responsive behavior across devices  
- Dark/Light mode switching  
- API data loading  
- Countdown accuracy  
- Form validation and feedback  
 