
📄 Simple Drag-Reveal Component
This project features a performance-optimized web component that uses a drag-and-swipe gesture to trigger a smooth transition between two background media elements.

It's built primarily using GSAP (GreenSock Animation Platform) for the interactive dragging and visual transitions.

🚀 How to Run
Save the files: Ensure you have the index.html, style.css, and script.js files saved in the same directory.

Include Dependencies: The project requires GSAP and the Draggable plugin. Make sure your index.html includes these scripts from a CDN:

HTML

<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/Draggable.min.js"></script>
Open: Open index.html in your web browser.

Interact: Click and drag the handle at the bottom of the screen horizontally to see the media transition.

⚙️ Technologies Used
GSAP (GreenSock): Used for smooth, physics-based dragging and declarative animations.

HTML/CSS: Provides the structure and styling, utilizing CSS variables for easy customization.

Custom JavaScript: Handles the efficient overlap detection logic using GSAP's onMove callback.

🎨 Customization
The colors and sizes can be easily adjusted using the CSS Variables defined in the :root section of style.css.

Variable	Function
--color-primary	Main indicator color (default: orange)
--drag-size	Size of the draggable handle (default: 3vw)
--transition-speed-slow	Duration of the opacity/video transition







