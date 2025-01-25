# Digital Clock

## Project Description
This project is a **Digital Clock** that displays the user's local time dynamically. The clock updates every second, providing an accurate representation of the current time in the user's timezone. The project leverages HTML, CSS, and JavaScript for its structure, styling, and functionality.

---

## File Descriptions

### 1. `index.html`
**Description:**  
The `index.html` file provides the basic structure of the digital clock application. Key features include:  
- A title banner that reads "Your Local Time".  
- A `div` element with the `id="clock"` where the real-time clock is dynamically updated.  
- Links to the external CSS (`style.css`) for styling and JavaScript (`script.js`) for functionality.

---

### 2. `style.css`
**Description:**  
The `style.css` file ensures that the application is visually appealing and user-friendly. It:  
- Sets a dark background (`#121111`) with white text for a clean, modern look.  
- Centers the clock both vertically and horizontally using Flexbox.  
- Styles the clock display with a large orange background, rounded corners, and padding for readability.  
- Includes a banner above the clock with a slightly smaller font size and proper alignment.

---

### 3. `script.js`
**Description:**  
The `script.js` file handles the dynamic functionality of the digital clock. It:  
- Selects the `clock` element using its `id`.  
- Uses the `setInterval()` method to update the displayed time every second.  
- Retrieves the current time using JavaScript's `Date` object and formats it using the `toLocaleTimeString()` method to match the user's local time.

---

## How It Works
1. When the webpage is loaded, the clock starts displaying the user's local time.
2. Every second, the `setInterval()` function updates the time on the screen by fetching the current time from the `Date` object.
3. The clock is styled with a bright orange background for emphasis and a modern design.

---

## Features
- **Real-Time Updates:** Displays and updates the local time every second.  
- **Responsive Design:** The clock is centered on the screen and visually optimized for various screen sizes.  
- **User-Friendly Interface:** Large, readable fonts and a clear layout make it easy to view the time.

---

## Example
- **Initial Display:**  
  - Banner: "Your Local Time"  
  - Clock: "10:35:23 AM" (or your local time)

---

Feel free to contribute or suggest improvements to this project!
