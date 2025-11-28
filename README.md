# Static Modal Window Demo

A simple **static modal window** built with **HTML and CSS**.  
This project demonstrates how to correctly layer UI elements using `z-index` so that a modal and its backdrop appear above the rest of the page content.

 **Live Demo:** https://static-modal.vercel.app

---

##  Features

-  **Always-visible modal** – the modal is statically displayed instead of being toggled with JavaScript.
-  **Centered overlay** – modal is positioned centrally on the screen.
-  **Dark backdrop** – a semi-transparent overlay darkens the background to draw attention to the modal.
-  **Correct z-index usage** – demonstrates how stacking contexts and `z-index` affect layering.
-  **Clean, semantic HTML** – easy to read and extend.
-  **Pure CSS styling** – no JavaScript framework or library required.

---

##  What This Project Teaches

- How to use `position` (likely `fixed` or `absolute`) to place a modal above the main content.
- How `z-index` controls the stacking order of:
  - the page content
  - the dark backdrop
  - the modal dialog itself
- Why the modal and backdrop must be in the correct order for proper visual hierarchy.

