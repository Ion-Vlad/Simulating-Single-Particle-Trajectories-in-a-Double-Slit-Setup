# Simulating-Single-Particle-Trajectories-in-a-Double-Slit-Setup
                 Read me for Double_Slit_Experiment_v1.1.html 

Copyright © 2025 Ion Vlad
This program is released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
When you modify or redistribute the code you must:
   • Keep this copyright notice intact.
   • Add a line “tweaked by <your name>” (or similar) after the notice.
   • If you rewrite the program in another language, keep the above notice visible in the UI/screenshots and include a link to the original repository: https://github.com/Ion-Vlad/Simulating-Single-Particle-Trajectories-in-a-Double-Slit-Setup
	or/and: https://drive.proton.me/urls/XG5ZKT94A8#ijnqZsisCgjv

Full license text: https://creativecommons.org/licenses/by/4.0/

Vlad, I. (2025). *Simulation of single‑particle trajectories in a double‑slit geometry* (Version 1.1) [Computer software]. Zenodo. https://doi.org/10.5281/zenodo.17922056


        Disclaimer:

	The program is built with HTML + JavaScript, allowing anyone to read the code and run it on most desktop browsers or Android devices without needing additional libraries or environments. For obvious reasons it works in Safari on desktop, but not on iPhone or iPad — I haven’t tested it on an Android tablet.
	Because this isn’t a programming‑project assignment, I wanted to keep the code as short and simple as possible, avoiding unnecessary graphics or functions that would be required to make it run on iPhone or iPad. I have tested it on an Android phone with Chrome, on Microsoft Edge and Opera on a PC, on Safari and Opera on a MacBook Pro, and on Linux.
	Since this program is meant solely for demonstration purposes and isn’t intended for in‑depth research, avoid running the simulation for long periods on low‑memory or slow computers.
  
	All files and documents related to this work (including additional screenshots) can be found here:
      
	https://drive.proton.me/urls/XG5ZKT94A8#ijnqZsisCgjv
      
	1. This program does not simulate how photons or waves behave; it merely demonstrates that particles can leave a “wave‑like” imprint on the screen even though they do not behave like waves. Reproducing the pattern does not falsify quantum mechanics, but highlights the importance of boundary interactions.
	2. Because the particles are emitted randomly, two simulations with identical parameters may produce slightly different imprints.
	3. Collisions between particles are not shown, as particles can be fired one at a time.
	4. At high speeds (> 4), a small particle can pass through a thin wall. This is normal single‑particle behaviour and should not be interpreted as a programming bug.
	5. The interface is self‑explanatory: adjust the settings and press Start. Some particles will pass through the slit and leave a red imprint on the screen. The particles that pass through the upper slit remain blue, whereas those that pass through the lower slit turn red.  This method records which slit each particle passes through without any physical interaction with the particles (or detectors).
	6. When enough particles have struck the screen, press Stop and analyse the imprint. You can press Start again if you want the imprint to “build up” further. 
	7. The Clear Screen button removes all red imprints and prepares the program for a new simulation, but it does not alter the current settings.
	8. During the simulation the sliders (controls) are disabled, and they become re‑enabled when the Clear Screen button is clicked.
	9. If the Screen Position setting is too high and the screen moves out of view, while the simulation is running (emitting), adjust the browser’s zoom level (or change the screen resolution) until the entire canvas fits within the viewport. Saving screenshots works best in Firefox by selecting Print → Save as PDF.
	10. Hover the mouse over the screen line to display a magnifier. This lets you inspect the imprint at the pixel level.
	11. The sliders can be adjusted incrementally with the arrow keys on the keyboard.
	12. In the 3‑D view, the number of visible dots can be fewer than the total number of particles that hit the screen. This occurs when multiple particles land at exactly the same coordinates; they overlap and appear as a single dot. In contrast, the 2‑D view records every impact individually, so the accumulation of dots is more reliable for detailed analysis. In 3‑D view mode the simulation runs considerably slower, so we cap it at 10 000 particles.
	13. Browser‑specific issues:
      	    a. Safari – Captures the 3‑D view correctly, but saves it as a flat rectangle, which can lead to misalignment in the imprint.
      	    b. Opera – The 3‑D view is captured accurately, yet the resulting image appears darker than the actual screen.
      	    c. Firefox – Saves the screenshot properly, but refreshing the page causes a strange misalignment and the sliders fail to update; a full page reload resolves the problem.
	    Note: The behaviour may vary depending on the computer hardware and browser version. It’s advisable to reload the page after each simulation.
	14. Do not run more than one simulation at the time, run the program in full-screen and prevent the computer from going to sleep.
