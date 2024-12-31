# Astigmatism Wheel Interactions

https://madalin-fr.github.io/AstigmatismWheelInteraction/

A dynamic web application visualizing an astigmatism wheel with interactive controls. This project allows users to manipulate various parameters of the visual display, including line thickness, color, opacity, and animation.

## Features

*   **Interactive Controls:**  A draggable control panel allows for adjusting:
    *   Line thickness and color
    *   Number of radiating lines
    *   Background and text colors
    *   Horizontal and vertical offsets
    *   Arc offset
    *   Line length
    *   Rotation speed
    *   Opacity
*   **Autopilot Modes:** Two autopilot modes with different behaviors for an animated display.
*   **Dark Mode:** Toggle between a light and dark user interface.
*   **Local Storage Persistence:**  Settings are saved in your browser's local storage.
*   **Responsive Canvas:** The canvas resizes to fill the browser window.
*  **Arrow-key Rotation:** Use the a/d keys to rotate the wheel, i/k for vertical shift, and j/l for horizontal shift.
*  **M-key Toggle**: Use the m key to switch between single or many line modes.

## How to Use

1.  **Open `index.html`:** Simply open the `index.html` file in your web browser.
2.  **Adjust Controls:** Use the draggable control panel to adjust settings.
    *   Click 'Show Controls' to open or close the settings.
    *   Drag the top of the controls to move the container.
3.  **Autopilot:** Start either autopilot mode for animated shifts and rotation.
4.  **Dark Mode:** Toggle the dark mode switch at the top of the controls panel.
5.  **Key Commands**: Try using the arrow keys to manipulate the image as described above.

## Technical Details

*   **HTML5 Canvas:** The main visual element is rendered using HTML5 `<canvas>`.
*   **JavaScript:** The core logic, interaction, and animation are handled with JavaScript.
*   **InteractJS:**  Used for the drag and drop controls.
*   **Font Awesome:** Icons are used to enhance the UI.
*   **Local Storage:** Settings are saved to the local storage and persisted across sessions.
*   **Responsive:** The canvas and layout are responsive to different browser sizes.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License.

[http://creativecommons.org/licenses/by-nc-sa/4.0/](http://creativecommons.org/licenses/by-nc-sa/4.0/)

© 2023 Jeremy Bornstein. All Rights Reserved.
© 2024 Frîncu Mădălin-Gabriel. All Rights Reserved.
