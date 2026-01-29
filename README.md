# Mad Libs Madness: Summer Camp Letter Generator

## Overview
This is a fun, lightweight, interactive web-based application that takes in user input to generate a custom "Letter from Summer Camp".
This project showcases DOM manipulation and dynamic HTML rendering.

## Live Demo
You can view the fully rendered project by using the link below:
- 📄 **Live Demo:**

### Tech Stack
- **HTML**
- **CSS**
- **JavaScript**

### Core Logic
- `formValue(id)` : Retrieves user input by it's ID. If entry box is left empty, the function will default to use the placeholder text to fill the missing entry.
- `addClassToElement(id, className)` : Is a reusable helper function that triggers visual changes on the page by dynamically adding the CSS classes to the specific HTML elements.
- `generate()` : Manages the workflow by using template literals to build a readable string template and updates the HTML to display the final output to the user.
