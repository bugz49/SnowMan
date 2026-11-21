3D Snow Man
A pure HTML, CSS, and GSAP animated snowman scene built with custom shapes, gradients, clip-path, and falling snow particles.

Project Structure
index.html — Page markup, snowman sections (hat, head, body, arms, rocks, base), and GSAP animation script.

clip.css — Styling for the night-sky gradient background, shapes, clip-path cuts, shadows, and snow container.

Features
CSS Shapes & clip-path: Uses border-radius, inset box-shadow, and clip-path: polygon() for the carrot nose and notched eyes.

GSAP Animations: Loads GSAP v3 via CDN to spawn 100 falling/drifting snowflakes, sway the stick arms, and animate eye movement and blinking.

How to Run
Keep index.html and clip.css in the same folder.

Open index.html in a browser (or run a local server like VS Code Live Server).

Ensure you have an internet connection so the GSAP CDN script loads.

Quick Tweaks
Snow count & size: Change totalFlakes or gsap.utils.random(5, 8) in index.html.

Arm wave & eye motion: Adjust rotation, x, scaleY, duration, and repeatDelay inside the GSAP <script> block.

Colors & spacing: Edit gradients, margins, and rem sizes in clip.css.