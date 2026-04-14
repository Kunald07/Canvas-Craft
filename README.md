# 🎨 CanvasCraft – Visual Design Editor (DOM Only)

CanvasCraft is a **Figma-style visual design editor (foundation version)** built using **pure HTML, CSS, and Vanilla JavaScript**.  
The project demonstrates strong understanding of **DOM manipulation, event handling, state management, and coordinate calculations**, without using Canvas, SVG, or any external libraries.


---

## 🚀 Project Objective

The goal of this project is to build a basic visual editor similar in spirit to Figma, using only standard DOM elements.  
The focus is on **correctness, clean logic, and real-world frontend fundamentals**, not performance optimizations or external engines.

---

## 🛠️ Tech Stack

- **HTML** – Structure  
- **CSS** – UI & Layout  
- **JavaScript (Vanilla)** – DOM manipulation & logic  
- ❌ No frameworks  
- ❌ No Canvas / SVG  
- ❌ No external libraries  

---

## ✨ Features

### 🔹 Element Creation
- Add **Rectangles**
- Add **Text Boxes**
- Each element has a unique ID, default size, and position

### 🔹 Selection System
- Single element selection
- Clear visual outline on selection
- Click on canvas to deselect

### 🔹 Drag, Resize & Move
- Drag elements using mouse
- Resize from corner handle
- Keyboard arrow keys for movement
- Elements stay inside canvas boundaries

### 🔹 Snap to Grid
- Optional snap-to-grid toggle
- Applies to drag, resize, and keyboard movement

### 🔹 Layers Panel
- Displays all elements in correct order
- Click layer to select element
- Move layers up/down (z-index control)

### 🔹 Properties Panel
- Edit width and height
- Change color
- Edit text content (for text elements)
- Live updates on change

### 🔹 Keyboard Shortcuts
- **Delete** → remove selected element
- **Arrow Keys** → move element

### 🔹 Save & Load
- Project auto-saves to `localStorage`
- Layout restores on page refresh

### 🔹 Export
- **JSON Export** – raw design data
- **HTML Export** – visual representation of the canvas

---

## 📦 Data Structure (Example)

```js
{
  id,
  type,
  x,
  y,
  width,
  height,
  color,
  text,
  zIndex
}


📌 Rules Followed

Built completely from scratch

No AI code copy-paste

Clean, readable, and well-structured code

All mandatory features implemented

Original UI and logic

🧠 Learning Outcomes

Deep understanding of DOM-based rendering

Mouse & keyboard event handling

Centralized state management

Coordinate calculations

Layer ordering logic

Real-world frontend architecture

👩‍💻 Author

Kunal Deshmukh
Frontend Developer | 

✅ Status

✔️ Project Completed
✔️ Ready for Evaluation
✔️ Fully Functional

⭐ Thank you for reviewing CanvasCraft!