🧮 Scientific Calculator (HTML, CSS, JS):

A fully functional scientific calculator built using HTML, CSS, and Vanilla JavaScript, supporting both basic and advanced mathematical operations.

🚀 Features

1. Standard Operations: +, -, ×, ÷, %, .

2. Scientific Functions:

	  -->Trigonometric: sin, cos, tan (in Degrees or Radians)

	  -->Exponential: exp(x)

	  -->Logarithmic: log(x)

	  -->Square root: √

	  -->Powers: x², x³

    -->Constants: π, e

	  -->Factorial: n!

3. Controls:

	  -->AC (All Clear)

	  -->⌫ (Delete last character)

	  -->Deg/Rad toggle

	  -->= (Calculate)

🛠 Tech Stack

HTML5: Structure

CSS3: Responsive layout and styling

JavaScript: Core calculator logic, expression parsing, and evaluation

📦 How It Works

1. User clicks on calculator buttons.

2. Input expression is shown in the display.

3. On pressing =, the expression is parsed:

	  -->Constants and functions are converted to JavaScript equivalents(e.g., π → Math.PI)

    -->Handles trigonometric modes and custom functions like factorial()

4. eval() is used to compute and return the result.

📱 Responsive Design

Mobile-friendly layout with media queries for smaller screens.

⚠️ Notes

No input validation for complex expressions (e.g., unbalanced parentheses).

Use of eval() can be risky in untrusted environments. (Safe here since there's no user-supplied code execution.)
