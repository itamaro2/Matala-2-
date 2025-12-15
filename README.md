# HTML & CSS Layout Challenge: Manual vs. AI (Copilot)

This project demonstrates four different approaches to building a specific responsive web layout. The primary goal was to practice foundational CSS concepts (Floats, Box Model) manually, and then compare that process with modern techniques (Flexbox, Bootstrap) generated with the assistance of GitHub Copilot.

📂 Project Structure & Entry Point

The project contains an index file that links to all four versions of the layout:

* **Main Index:** `Hagasha.HTML` - Open this file to navigate between the different implementations.

🛠️ Implementations

1. Manual Implementation (Student Work)
* **Files:** `manual.html`, `manual.css`
* **Methodology:** "Old School" CSS Floats.
* **Description:** This version was written entirely by hand without AI assistance.
* **Key Technical Details:**
    * **Custom Grid System:** A 12-column grid built from scratch using percentage widths (e.g., `.col-3 { width: 25%; }`).
    * **Positioning:** Relies on `float: left` for horizontal alignment.
    * **Structure:** Uses specific IDs (`#id1` through `#id15`) to control the height and nesting of elements.
    * **Responsiveness:** Includes a media query (`max-width: 750px`) that disables floats and stacks elements vertically for mobile devices.

### 2. Copilot Plain (AI Generated)
* **Files:** `Copilot_Plain.html`, `Copilot_Plain.css`
* **Methodology:** CSS Floats (AI Variation).
* **Description:** An AI-generated recreation of the manual float-based approach.
* **Comparison:** Unlike the manual version which uses numbered IDs, the AI used semantic class names like `.sidebar`, `.top-row`, and `.mid-left`. It serves as a comparison of how code structure differs between a human beginner and an AI model using the same underlying technology (Floats).

3. Flexbox Implementation (AI Generated)
* **Files:** `flex.html`, `flex.css`
* **Methodology:** Modern CSS Flexbox.
* **Description:** A modern, cleaner approach that avoids floats entirely.
* **Key Technical Details:**
    * Uses `display: flex`, `flex-direction: column/row`, and `gap` for spacing.
    * **Height Management:** Utilizes percentage heights (e.g., Top 18%, Mid 50%, Bottom 28%) for desktop, and `vh` (viewport height) units for mobile responsiveness.
    * **Semantic HTML:** Uses tags like `<aside>` and `<main>`.

4. Bootstrap 5 Implementation (AI Generated)
* **Files:** `bootstrap.html`, `bootstrap.css`
* **Methodology:** CSS Framework.
* **Description:** Utilizes the Bootstrap 5 library to achieve the layout with minimal custom CSS.
* **Key Technical Details:**
    * Leverages utility classes such as `container-fluid`, `row`, `col-md-3`, and `d-flex`.
    * Includes a small custom CSS file (`bootstrap.css`) solely to enforce `min-height` requirements that standard Bootstrap classes didn't cover by default.

-----------------

🤖 Authorship & Credits

* **Manual Implementation:** Written 100% by the student to demonstrate understanding of core CSS mechanics.
* **Copilot Plain, Flexbox, & Bootstrap:** Generated using **GitHub Copilot** to explore how AI handles different CSS methodologies and framework integration.

🚀 How to Run
1.  Clone or download the repository.
2.  Open `Hagasha.HTML` in any web browser.
3.  Click the links to view the different versions.
