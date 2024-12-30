# Spot the Difference Game with Cropping Tool 🎮✂️

## Description 📝

This project is a combination of a **Spot the Difference Game** 🔍 and a **Cropping Tool** ✂️ built using HTML5, CSS3, and JavaScript 💻. It allows users to load an image 🖼️, select specific parts by cropping, and dynamically view those cropped sections in a dedicated panel 📋. Each cropped section is accompanied by a delete button ❌ to remove the selection. This is ideal for interactive games 🎮 or applications where users identify differences 🔄 in images.

---

## Features ⭐

1. **Spot the Difference Game** 🔍:
   - Allows users to upload an image 🖼️ to play the game 🎮.
   - Users can mark regions 📍 on the image that they think differ from another image 🖼️.
   - Stores user-selected regions 📂 for comparison.

2. **Cropping Tool** ✂️:
   - Enables users to crop parts of the image dynamically ✏️.
   - Displays cropped sections in a side panel 📋 with an option to delete ❌ them.
   - Maintains the coordinates 📐 of all cropped sections for potential validation or game logic 🎯.

3. **Responsive Design** 📱:
   - The canvas and cropped image container adapt to different screen sizes 🖥️📱, ensuring usability across devices.

4. **Interactive UI** 🖲️:
   - Red selection rectangle 🟥 for real-time feedback while cropping.
   - Easy-to-use delete button ❌ for each cropped section.

---

## Setup Instructions 🛠️

### Prerequisites ✅
- A modern browser 🌐 (Chrome, Firefox, Edge, etc.) with support for HTML5 Canvas and JavaScript 💻.
- No additional software or libraries 📦 are required.

### Steps 🚀
1. Clone or download this repository 🗂️.
2. Open the `index.html` file in any browser 🌐.
3. Interact with the application 🎮:
   - Upload an image using the file input 🖼️.
   - Crop parts of the image using the canvas ✏️.
   - View and manage cropped sections in the side panel 📋.

---

## Usage 🖱️

1. **Uploading an Image** 🖼️:
   - Click on the "Choose File" button 📂 to upload an image 🖼️.
   - Once uploaded, the image will appear on the canvas 🖌️.

2. **Selecting Regions** 📍:
   - Click and drag 🖱️ on the canvas to select a region 🔲. A red rectangle 🟥 will highlight the selected area.
   - Release the mouse 🖱️ to finalize the selection ✔️.

3. **Viewing Cropped Sections** 👀:
   - Cropped sections will appear in the right panel ➡️📋.
   - Each cropped image has a cross button (`X`) ❌ to delete the section.

4. **Deleting a Selection** ❌:
   - Click the cross button ❌ next to a cropped image 🖼️ to remove it from the list 📂 and delete its coordinates 📐.

---

## Code Details 💻

### Core Files 📂
1. `index.html`: Contains the HTML structure 🏗️ for the application.
2. `style`: Inline CSS 🎨 defines the layout and styles for the canvas, buttons, and side panel.
3. `script`: JavaScript implements the image cropping functionality ✂️, dynamic updates 🔄, and interaction logic 🖲️.

### Key Functionalities ⚙️
1. **Canvas Drawing** 🖌️:
   - Dynamically resizes based on the uploaded image 🔄.
   - Tracks mouse events 🖱️ for cropping regions 📍.
   
2. **Cropped Image Management** 🗂️:
   - Dynamically generates new `canvas` elements 🖌️ for each crop ✂️.
   - Adds delete functionality ❌ using a unique ID for each cropped section 🆔.

3. **Part Selections** 📐:
   - Stores crop coordinates 📂 and ensures synchronization 🔄 when sections are added or removed ✏️.

---

## Possible Enhancements 🚀

1. **Spot the Difference Validation** ✅:
   - Implement logic to compare user-selected regions 📍 with predefined differences 🖼️.
   - Provide feedback (e.g., correct/incorrect) ✔️❌ for each selection.

2. **Multiple Image Support** 🖼️:
   - Allow users to upload two images 🔄 and switch between them for spotting differences 🔍.

3. **Scoring System** 🏆:
   - Add a scoring mechanism 🔢 to track correct and incorrect guesses ✔️❌.

4. **UI Improvements** 🎨:
   - Improve the design 🎨 with additional CSS or frameworks like Bootstrap 🌐.

---

## License 📜

This project is open-source 🆓 and free to use ✨. Feel free to modify or enhance it as per your needs 🔧.

---

## Author 👤

**Abhishek Sahoo** 👨‍💻

---

If you have any further questions ❓ or need assistance 🤝, feel free to reach out 📩!

