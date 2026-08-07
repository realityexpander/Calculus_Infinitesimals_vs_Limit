# Calculus Visualizer
## Definition of a derivative Infinitesimals vs. Limits

<a href="https://realityexpander.github.io/Calculus_Infinitesimals_vs_Limit/">
 <img width="524" src="https://github.com/user-attachments/assets/5ddf1cd3-4d29-4576-ab84-05efd60b01e8" alt="image">
</a>

http://github.io/realityexpander/Calculus_Infinitesimals_vs_Limit

An interactive, browser-based simulation that provides a side-by-side visual comparison of two foundational approaches to calculus: standard limit theory and non-standard analysis (infinitesimals). 

Public link to Gemini AI Conversation that generated the initial code:
https://share.gemini.google/o2XF5bAkUmZo

## 🚀 Features
* **Interactive HTML5 Canvas:** Renders dynamic curves, secant lines, and tangent lines in real-time.
* **Limit Approach Panel:** Visualizes the secant line approach as step size ($h$) approaches zero, highlighting the standard $\epsilon-\delta$ conceptual framework.
* **Infinitesimal Approach Panel:** Features an interactive "hyperreal microscope" that demonstrates how a curve becomes perfectly straight at infinite magnification, modeling $dx$ and $dy$ as discrete, non-zero fractions.
* **Real-Time Controls:** 
  * Adjust the base coordinate ($x$) to move along the curve.
  * Modify the limit step size ($h$) to see the secant line converge.
  * Change the microscope magnification to observe local linearity.

## 🛠 Tech Stack
* **HTML5 / CSS3:** Responsive layout and UI styling.
* **Vanilla JavaScript:** Core logic, state management, and math functions.
* **Canvas API:** High-performance 2D rendering.

## 💻 How to Use
This project has zero dependencies. Simply clone the repository and open the file in any modern web browser:

1. `git clone https://github.com/yourusername/calculus-visualizer.git`
2. Open `index.html` in Chrome, Firefox, Safari, or Edge.

## 📝 License
This project is licensed under the MIT License.
