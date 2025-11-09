# 💡 Soft UI Shadow Playground | Neumorphism Code Generator

This is a real-time, single-file web application designed to help developers and designers easily create and customize **Soft UI (Neumorphic)** shadows and gradients.

Adjust physical lighting parameters—such as the light source angle, shadow distance, and the card's perceived elevation—to instantly generate and copy the corresponding CSS and Flutter code.

## ✨ Key Features

* **Real-time Preview:** Instantly see how changes affect the card's appearance.

* **Controllable Parameters:** Fine-tune the effect with five key sliders:

  * **Light Angle:** Controls the direction of the light source.

  * **Shadow Distance:** Affects the size and spread of the shadow.

  * **Card Elevation (Z-Axis):** Controls the overall intensity of the effect.

  * **Inner Light Intensity:** Scales the offset and blur of the inner highlight, controlling the card's perceived volume.

  * **Base Surface Color:** Change the primary color of the design.

* **Dual Code Output:** Generates code snippets for both **Web (CSS)** and **Mobile (Flutter)**.

* **Dark/Light Mode:** Toggle between light and dark themes to ensure your design works in both contexts.

## 🚀 How to Use the Generator

1. **Open the Tool:** Simply open the `index.html` file in any modern web browser.

2. **Adjust Parameters:** Use the sliders in the "Shadow Parameters" panel to find your desired Neumorphic style.

3. **Preview:** Observe the "Preview Card" for the live render of your shadow configuration (which uses a combination of outer drop shadow and inner inset light shadow).

4. **Copy Code:** Switch between the **CSS Output** and **Flutter Output** tabs and copy the generated `box-shadow` or `BoxShadow` properties directly into your project.

## 💻 Tech Stack

This project is intentionally built using minimal, standard technologies for maximum simplicity and portability:

* **HTML5**

* **JavaScript (Vanilla):** For all calculations and DOM manipulation.

* **Tailwind CSS:** For fast, utility-first styling and responsive design.

## License

This project is licensed under the MIT License.
