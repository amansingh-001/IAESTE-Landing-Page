# IAESTE LC JECRC — Modern Landing Page  
A fully animated, visually rich landing page built using **HTML, CSS, and JavaScript**, featuring parallax motion, glowing gradient borders, animated hero sections, and a custom sign‑in modal.

This UI is inspired by modern tech websites and designed for the IAESTE LC JECRC student chapter.

---

## 🎯 Project Overview

This website is a redesigned front‑end version of the IAESTE LC JECRC page featuring:

- A futuristic landing page with layered hero graphics
- Smooth parallax movement based on mouse position
- Animated gradient border frames
- Hover‑based glow effects
- Interactive sign‑in modal window
- Fully responsive layout across breakpoints
- Clean aesthetic suitable for student organisations

---

## 🚀 Features

### 🌌 **Hero Section**
- Multi‑layer image composition  
- Parallax animation on mouse movement  
- Highlighted slogan text  
- Call‑to‑action button  
- Animated video inside a gradient frame  

### ✨ **Gradient Elements**
- Hex‑clipped gradient borders  
- Hover glow shadow  
- Used for bottom image list & sign‑in button border

### 🔐 **Sign‑In Modal**
- Smooth open and close animations  
- Blur + fade‑in effects  
- Clickable close icon  
- Styled input fields and button

### 🎨 **Design Characteristics**
- Dark theme  
- Neon gradients  
- Monospace + serif font blend  
- Strong visual focus  
- Motion‑based interaction  

---

## 📁 Project Structure

```
/IAESTE-LC-JECRC
│
├── index.html          # Main HTML Structure
├── style.css           # Full styling, gradients, layout, animations
├── app.js              # Parallax, modal animations, interactions
└── images/             # All graphics, elements, icons, video files
```

---

## 🛠️ Technologies Used

- **HTML5** (semantic structure)
- **CSS3**  
  - gradient borders  
  - clip-path shapes  
  - keyframe animations  
  - responsive design  
- **JavaScript (Vanilla)**  
  - event listeners  
  - animation triggers  
  - parallax transformation  
  - modal open/close system  
- **Boxicons** for icons

---

## 📦 Setup Instructions

1. Download or clone the project:
```bash
git clone https://github.com/yourusername/iaeste-lc-jecrc.git
```

2. Place all images inside the `/images` directory.

3. Open the project:
```bash
open index.html
```
or just double‑click **index.html**

---

## 📱 Responsive Behavior

- Header collapses on small screens  
- Bottom image strip wraps automatically  
- Hero text reduces font size  
- Sign‑in modal scales according to screen width  

---

## 🧩 JavaScript Functionalities

### 🌀 Parallax Animation
```js
document.addEventListener("mousemove", (event)=>{
   ...
});
```

### 🔓 Sign‑In Open
```js
signinPage.classList.add("openSignin");
```

### ❌ Close Modal
```js
signinPage.classList.add("closeSignin");
```

---

## 🎨 Customization Guide

### 🔸 Change gradient colors  
In **style.css**, modify:
```css
background: linear-gradient(to right, #00aaa7, #7f42a7, ...);
```

### 🔸 Update hero text  
In **index.html**, modify:
```html
<h1>WORK . EXPERIENCE . DISCOVER</h1>
```

### 🔸 Replace video  
Place your new video in `/images` and update:
```html
<video src="images/vid1.mp4" ...>
```

---

## 📜 Credits

- **Designed & Coded by Aman Singh**
- IAESTE LC JECRC  
- Boxicons CDN  
- Students contributing images & content  

---

