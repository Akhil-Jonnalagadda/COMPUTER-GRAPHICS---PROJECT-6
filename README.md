# 3D Robot Arm with Finger Control – WebGL Project

## Overview

This project implements an interactive **3D Robot Arm** simulation using **WebGL**. The robot consists of a base, lower arm, upper arm, and three fingers—each with its own 3 degrees of rotational freedom along the X, Y, and Z axes.

Users can manipulate each joint using sliders, allowing for real-time visualization and testing of hierarchical modeling and transformation matrices.

---

## Features

- ✅ **Full 3D Hierarchical Robot Arm**
  - Base, Lower Arm, Upper Arm, and 3 Fingers.
  - Each component supports rotation around X, Y, and Z axes.

- 🎛 **Interactive Controls**
  - 18 sliders for angle manipulation.
  - Individual rotation control for each body part and finger.

- 🎨 **Color and Geometry**
  - Color-coded cube rendering.
  - Reusable cube geometry used to construct each arm segment.

- 💡 **Matrix & Shader Management**
  - Uses transformation matrices (modelViewMatrix, projectionMatrix).
  - Written in GLSL shaders for vertex transformation and coloring.

---

## Technologies Used

- WebGL (via `webgl-utils.js`)
- GLSL Shaders (inline in HTML)
- HTML5 + JavaScript
- `MV.js` for matrix and vector math utilities

---

## File Structure

| File               | Purpose                                               |
|--------------------|-------------------------------------------------------|
| `robotArm.html`    | HTML file with embedded shaders and sliders           |
| `robotArm.js`      | JavaScript controlling 3D rendering and interactions  |
| `MV.js`            | Math utilities for vector/matrix transformations      |
| `webgl-utils.js`   | WebGL context and animation helper                    |
| `initShaders.js`   | Shader program initialization logic                   |

---

## How to Run

1. Download or clone the repository.
2. Open `robotArm.html` in a WebGL-supported browser (e.g., Chrome, Firefox).
3. Use the sliders to rotate each part of the robot arm along desired axes.
4. Observe the hierarchical updates reflected in real-time on the canvas.

---

## Lessons Learned

- Mastered the concept of **hierarchical transformations** in 3D.
- Learned **real-time UI binding** using sliders to update 3D objects.
- Developed proficiency with **WebGL shaders** and attribute buffers.
- Gained experience in **modular code organization** using MV and shader utility scripts.

---

## Known Issues

- ⚠ None – the project is currently **fully functional** with no bugs.


## Future Improvements

- Add **animation toggle** to automate arm motion.
- Export pose data for saving/loading configurations.
- Enhance visuals using lighting and shading techniques.

---

## License

Open-source for educational purposes.

