Navigate the Interface:
The app opens with a dark-themed window.
Use the sidebar on the left to switch between calculator types: Basic Arithmetic, EMI Calculator, Differential Calculus, Integral Calculus, and Logarithmic Calculations.
Using Each Calculator:
Basic Arithmetic:
Click the buttons (0-9, +, -, *, /, etc.) to input an expression.
Press = to compute the result, or C to clear the display.
EMI Calculator:
Enter the loan amount, annual interest rate (%), and number of monthly installments.
Click "Calculate EMI" to see the monthly payment.
Differential Calculus:
Enter a function (e.g., x**2 + sin(x)).
Click "Differentiate" to compute the derivative.
Integral Calculus:
Enter a function (e.g., x**2).
Click "Integrate" to compute the indefinite integral (includes +C).
Logarithmic Calculations:
Select the logarithm type (Natural, Common, or Custom Base).
Enter the number (and base, if custom).
Click "Calculate" to see the result.
Feedback:
Results appear in the main area.
The status bar at the bottom provides feedback (e.g., "Calculation successful" or error messages).
Features
Aesthetic Design:
Dark background (#2c2c2c) with metallic button accents (#4c4c4c).
Elegant serif font ("Palatino Linotype") for a classy look.
Clean layout with a top bar, sidebar, and responsive main area.
Functionality:
Basic Arithmetic: Supports addition, subtraction, multiplication, division, and decimal points with error handling (e.g., division by zero).
EMI Calculator: Calculates monthly EMI using the formula:
EMI = P * R * (1 + R)^N / ((1 + R)^N - 1)
where P is the principal, R is the monthly rate, and N is the number of installments.
Calculus: Uses SymPy for symbolic differentiation and integration of functions (e.g., sin(x), exp(x)).
Logarithms: Computes natural (ln), common (log10), and custom-base logarithms using Python’s math module.
Error Handling:
Validates inputs (e.g., positive numbers for EMI and logarithms).
Displays clear error messages for invalid inputs or calculations.
