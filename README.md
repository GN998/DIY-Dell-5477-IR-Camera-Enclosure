# Dell Inspiron 5477 Camera Module Windows Hello Enclosure

<img width="983" height="534" alt="image" src="https://github.com/user-attachments/assets/92d82cb4-9e28-4cdb-9beb-7baf08335f1b" />


This is a 3D printable enclosure designed for the salvaged camera module from a Dell Inspiron 5477 All-in-One PC. The project aims to DIY this excellent camera (including infrared functionality) into a standalone USB-C camera that supports Windows Hello.
This repository only provides the 3D model files for the enclosure and does not include detailed circuit wiring tutorials.

---

## ✨ Features

*   **Precise Fit**: Specifically designed for the salvaged Dell Inspiron 5477 camera module, ensuring a perfect fit.
*   **Modern Interface**: Integrates a USB-C female port for convenient connection.
*   **Built-in Circuit Space**: Internal space is reserved for a 5V to 3.3V step-down module.
*   **Easy Installation**: The enclosure features an M3*4 nut insert slot, which can be used for mounting on a stand or securing to a monitor.
*   **Simple Design**: Simple structure, easy to 3D print and assemble.

## 🔩 Bill of Materials (BOM)

To complete the entire project, you will need the following components:

1.  **3D Printed Parts**:
    *   `case-main.stl` (Main Enclosure)
    *   `case-lid.stl` (Back Lid)
2.  **Electronic Components**:
    *   Dell Inspiron 5477 salvaged camera module
    *   One 5V to 3.3V step-down circuit board (e.g., AMS1117-3.3V module)
    *   One USB-C female Breakout Board (dimensions: length 10.00mm, width 7.5mm, height 6.5mm)
    *   Several jumper wires, recommended 26 & 24 AWG gauge, 5cm length
3.  **Hardware**:
    *   1 x M3*4 heat-set insert nut (for stand mounting)

**Important Notes:**
The copper on the back of the Inspiron 5477 camera is conductive; it is recommended to apply a layer of insulating material.

## 🛠️ Printing & Assembly Suggestions

### Printing Suggestions

*   **Material**: PETG or ABS are suitable, or you can choose resin for SLA/DLP printing. The heat dissipation of the camera module is currently unknown.

### Assembly Steps

1.  Print the `case-main.stl` and `case-lid.stl` files.
2.  Use a soldering iron to embed the M3*4 heat-set insert nut into the reserved hole in the main enclosure.
3.  Place the USB-C female port and the 5V to 3.3V circuit board into their respective slots inside the enclosure. A small amount of hot glue can be used to secure them.
4.  According to the pin definition of the camera module, use jumper wires to connect the camera, step-down module, and USB-C interface.
    > **Note**: Before wiring, please ensure you have correctly identified the camera module's pinout. Incorrect wiring may damage the camera!
5.  Carefully place the camera module into the front slot of the enclosure.
6.  Arrange the internal cables, close the back lid (`case-lid.stl`).
7.  (Optional) Use an M3 screw to mount the assembled camera onto your designed stand or monitor.

## 🤝 Contributing

Contributions in any form are welcome! If you have any suggestions for improving the model (e.g., adapting it for different sizes of step-down modules), please feel free to submit a Pull Request or create an Issue.

## 📜 License

This project is licensed under the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)** license.

[![CC BY-NC-SA 4.0](https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-nc-sa/4.0/)

In simple terms, you are free to:

*   **Share**: Copy and redistribute the material in any medium or format.
*   **Adapt**: Remix, transform, and build upon the material.

As long as you follow the license terms, the licensor cannot revoke these freedoms. You must abide by the following conditions:

*   **Attribution**: You must give appropriate credit, provide a link to the license.
*   **NonCommercial**: You may not use the material for commercial purposes.
*   **ShareAlike**: If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original.

---
*Disclaimer: This is a DIY project. The author is not responsible for any damage to your components. Please proceed with caution.*
