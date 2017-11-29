# CSC5210_FinalProject

---
First-person cliff diving game.

User will be able to run and jump and perform flips. If the user lands in the water incorrectly or does not jump on time, an
ambient light will make the screen glow red. The scene will include point lights that glow red when the user is unable to jump and green when it is okay to jump.

---

Project source code can be downloaded from https://github.com/MC-CSC5210/CSC5210_FinalPoject.git

---

Author and Contributor List
---

John Wyeth

Thomas Kelley

Pat Langille

---

To Be Done
---

**Terrain:**

 - textured
 - large
 - water (collision detection)
 - tesselation/geometry shader for cliff and water
 
 
 **First-Person View:**
 
 - 'f' will rotate the camera to simulate a flip
 - 'r' will rotate the camera to simulate a backflip
 - camera will be translated based on simulated gravity
 
 
 **Lighting and Shaders:**
 
 - scene should be lit using ambient light (turns red as a result of a bad dive)
 - scene should be lit using directional light from above the scene(like the sun)/will be toggled on and off using 'T' (maybe)
 - scene should have two point lights at the top of the cliff which are red prior to the jump and green when the user can jump
 
 
 How to Use
 ---
 
 1. 'J' will initiate the run leading to the jump
 2. 'Space' will allow the user to jump
 3. 'F' will allow the user to perform a front-flip
 4. 'R' will allow the user to perform a back-flip
 5. user will then be prompted if they'd like to jump again


