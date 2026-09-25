# ⚡ Pokémon Gen I — Pikachu UI Recreation

## 📌 Project Overview

A **frontend UI recreation project** built from scratch using **HTML5 and CSS3**, based on a provided Pokémon-themed visual design.

The primary objective of this project was to understand and implement **CSS positioning properties** such as `position: relative` and `position: absolute` while recreating a complete UI layout as closely as possible to the reference design.

Rather than using a CSS framework, the interface was constructed using **core CSS layout and positioning techniques** to strengthen fundamental frontend development skills.

---

## 🎯 Project Objective

The project was created as a practical exercise to understand how individual UI elements can be positioned, aligned, layered, and composed into a complete visual interface.

### Main Focus

* CSS `position: relative`
* CSS `position: absolute`
* Flexbox layout
* Element positioning using `top` and `left`
* Parent-child positioning relationships
* Typography and spacing
* CSS gradients
* Image positioning
* Decorative element layering
* UI composition

---

## 🛠️ Technologies Used

| Technology           | Purpose                          |
| -------------------- | -------------------------------- |
| **HTML5**            | Semantic page structure          |
| **CSS3**             | Styling and visual layout        |
| **CSS Positioning**  | Precise placement of UI elements |
| **Flexbox**          | Content alignment and spacing    |
| **CSS Gradients**    | Background visual composition    |
| **Remix Icon**       | Menu icon                        |
| **SVG / PNG Assets** | Pokémon visual elements          |

---

## 📊 Project Metrics

* **1** HTML document
* **1** CSS stylesheet
* **1** primary UI layout
* **5** navigation indicator points
* **3** major visual assets
* **1** Remix Icon
* **320px** maximum text-content width
* **400 × 400px** Pokémon image area
* **150px** Pokémon logo width
* **170 × 170px** decorative Poké Ball
* **100px** primary heading size
* **20px** primary content gap
* **12px** indicator and internal spacing
* **60/40** two-tone background gradient composition

---

## 🧩 Key CSS Concepts Implemented

### 1. Relative Positioning

The main layout acts as the positioning reference:

```css
.layout1 {
    position: relative;
}
```

This allows absolutely positioned child elements to use `.layout1` as their containing block.

---

### 2. Absolute Positioning

Major visual elements are positioned precisely using:

```css
.poko {
    position: absolute;
    left: 600px;
    top: 80px;
}
```

This was particularly useful for recreating the reference design where elements occupy specific visual positions.

---

### 3. Flexbox

The text section uses a vertical Flexbox layout:

```css
.textContent {
    display: flex;
    flex-direction: column;
    gap: 20px;
}
```

This helped maintain consistent spacing between the different content elements.

---

### 4. Gradient Background

The primary background uses a two-tone linear gradient:

```css
background: linear-gradient(
    to right,
    #FCC60C 60%,
    #FBE8B5 40%
);
```

This creates the main visual division between the two background areas.

---

### 5. Overflow Control

Decorative elements are clipped using:

```css
.layout1 {
    overflow: hidden;
}
```

This prevents elements extending outside the main layout from becoming visible.

---

### 6. Typography Control

The main heading uses a large display size with controlled line height:

```css
.textContent h1 {
    font-size: 100px;
    font-weight: 600;
    line-height: 1;
}
```

This helped control the visual height of the heading and maintain the intended spacing within the Flexbox layout.

---

## 🎨 UI Components

The interface contains several visually distinct elements:

1. **Pokémon Logo**
2. **Pikachu Character Image**
3. **Poké Ball Decorative Element**
4. **Menu Icon**
5. **Vertical Navigation Indicators**
6. **Generation Label**
7. **Large Pikachu Heading**
8. **Description Content**
9. **Slide/Page Indicator**

---

## 🧠 Key Learnings

This project helped reinforce several important frontend concepts:

* Understanding the difference between **relative and absolute positioning**
* Understanding how an element's **containing block** affects absolute positioning
* Using Flexbox for structured content layouts
* Controlling spacing with `gap`
* Understanding how `line-height` affects text layout
* Combining typography with visual hierarchy
* Positioning images independently from normal document flow
* Using gradients to create visual sections
* Controlling overflowing decorative elements
* Recreating a UI from a visual reference instead of designing only from scratch

---

## 🔍 Development Approach

The project was developed through an iterative process:

```text
Reference Design
      ↓
Analyze Layout
      ↓
Identify Positioning Relationships
      ↓
Create HTML Structure
      ↓
Implement CSS Positioning
      ↓
Adjust Typography & Spacing
      ↓
Position Images & Decorative Elements
      ↓
Refine Visual Layout
```

The focus was not only on reproducing the appearance but also on understanding **why each CSS property was required**.

---

## 📁 Project Structure

```text
Pokemon-UI/
│
├── index.html
├── style.css
│
└── asset/
    ├── pokemon_logo.svg
    ├── colored_pokenmon.png
    └── pokemon_ball.svg
```

---

## 🚀 Future Improvements

Potential improvements for future iterations:

* Add responsive layouts for mobile and tablet screens
* Replace fixed positioning values with more flexible layout techniques
* Add interactive navigation between Pokémon
* Add hover and transition effects
* Improve accessibility
* Optimize image assets
* Add JavaScript-based interactions
* Convert the static UI into a reusable component-based interface

---

## 🔗 Project Links

**GitHub Repository:**
`ADD_GITHUB_LINK_HERE`

**Live Demo:**
`ADD_LIVE_LINK_HERE`

---

## 📌 Project Type

**Frontend UI Recreation / CSS Positioning Practice**

### Core Skills Demonstrated

`HTML5` · `CSS3` · `CSS Positioning` · `Flexbox` · `UI Recreation` · `Typography` · `Layout Design` · `Visual Composition`
