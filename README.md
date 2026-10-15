MATLAB GUI Calculator 

A desktop calculator built with MATLAB App Designer (MATLAB version R2026a). 
Features include:
1. A number pad (0-9) and a decimal point button
2. Addition, subtraction, multiplication, and division
3. Square and square-root buttons
4. "=" button that evaluates the full expression shown on the calculator's display
5. Clear button that resets the calculator's display
6. Status lamp: green for valid calculation, red for invalid input, gray after a reset
<img width="430" height="306" alt="image" src="https://github.com/user-attachments/assets/7715e0a0-13a4-41bc-be7e-adcda7b11c41" />


Each button has a callback function that updates the display text. The Enter button evaluates the expression and shows the result. If the expression is invalid, the display shows "Error" and the lamp turns red. 

Limitations and Future Improvements
- The number buttons should all share one callback instead of ten separate callbacks.
- Planned additions: backspace, parentheses, a calculation history.

Author: Emily Meagher
