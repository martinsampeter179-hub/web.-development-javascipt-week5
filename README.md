# SpendWise — JavaScript Foundation

SpendWise is a modern personal finance tracking dashboard application. In this iteration, the project transitions from a visual prototype into a dynamic web application capable of collecting financial data, processing spending metrics, and logging budget calculations.

## JavaScript Concepts Implemented

1. **Variables & Scope:** Used `let` for values requiring calculation updates (e.g., `totalMonthlyBudget`, `foodExpense`) and `const` for static configuration values (e.g., `currencySymbol`).
2. **Data Types & Type Conversion:** Handled string outputs from window prompts and parsed them into numerical floating-point values using `parseFloat()`.
3. **User Inputs:** Interactively collected budget parameters from users via `prompt()` functions.
4. **Arithmetic Operators:** Utilized addition (`+`), subtraction (`-`), division (`/`), and multiplication (`*`) operators to calculate financial metrics.
5. **Reusable Functions:** Structured application logic into distinct, single-responsibility functions with parameters and return statements.
6. **Console Logging:** Standardized output reporting using `console.log()`, `console.warn()`, string interpolation, and `.toFixed(2)` number formatting.

## Usage & Execution

1. Open `index.html` in your web browser.
2. Respond to the sequence of prompt boxes requesting budget and category expense numbers.
3. Open the browser Developer Tools (`F12` or `Ctrl + Shift + I` / `Cmd + Option + I`), and navigate to the **Console** tab to inspect your formatted **SpendWise Financial Report**.
