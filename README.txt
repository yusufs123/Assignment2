# Assignment2
README

File Organization:
The project consists of three main files:
1. index.html: Contains the structural markup with a container div and 6 child divs (A-F).
2. styleA.css: Handles the vertical layout using CSS Flexbox properties (justify-content: space-evenly) to ensure responsive vertical spacing.
3. styleB.css: Handles the horizontal layout using 'display: inline-block' and 'white-space: nowrap' to prevent wrapping. It uses 'position: fixed' for the final element to keep it in the bottom-right corner.

Challenges Faced:
- Ensuring the vertical spacing in Style A remained equal regardless of window height was solved using Flexbox's 'space-evenly'.
- In Style B, preventing the boxes from wrapping when the window size was reduced required using 'white-space: nowrap' on the container.
- Positioning the text correctly inside the boxes (especially vertically centering in Style A's last box vs. padding in Style B) required careful usage of Flexbox alignment and padding properties respectively.
