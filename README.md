# ✦ TaskFlow — To-Do List

An editorial, Art-Deco minimal task management application engineered for streamlined productivity. Designed with a striking dark charcoal aesthetic and electric lime accents, TaskFlow pairs premium typography with high-fidelity micro-interactions to create a highly satisfying workflow environment.

---

## ⚡ Features

* **State Persistence:** Automatically saves your workflow using `localStorage` so tasks remain intact upon page reload.
* **Dynamic Metrics Reporting:** Real-time metrics engine calculating **Total**, **Active**, and **Completed** tasks, paired with a fluid animated CSS transition progress bar.
* **Priority Tiering:** Multi-tiered urgency allocation (`Low 🟢`, `Medium 🟡`, `High 🔴`) styled using custom sidebar dynamic border tags.
* **Advanced Contextual Filtering:** Instantaneous live view updates across full, pending (`Active`), or resolved (`Completed`) lifecycles.
* **Performance Optimized UI Elements:** Includes entry/exit layout animation keyframes, dynamic component element shaking upon validation failure, and specialized safety checks like programmatic XSS/HTML escaping.

---

## 📂 Project Architecture

The application is engineered completely with pure vanilla web technologies:

```filepath
├── index.html       # Semantically structured DOM layout and CDN font payloads
├── style.css        # Fluid typography, custom properties, and multi-layered CSS mesh backgrounds
└── script.js        # Scoped IIFE encapsulation layer driving State, Persistence, and Rendering
