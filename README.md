
## Description
Android Shooter is a first‑person shooter built in Unreal Engine 5, designed to demonstrate the core systems and gameplay mechanics required for a functional FPS experience. The project showcases AI behavior, animation systems, combat logic, and environmental interaction inside a fully navigable industrial facility.

## Gameplay
Upon launching the game, players enter a large factory environment populated with hostile android enemies. The objective is to navigate through the facility, eliminate all enemy units, and survive the encounter.

The game includes:

Responsive FPS movement and shooting mechanics

Enemy androids driven by AI behavior trees

Particle effects for muzzle flashes, impacts, and explosions

Sound effects for weapons, footsteps, and enemy alerts

Smooth character and enemy animations

A restart option if the player is defeated

The experience is designed to feel dynamic, reactive, and visually engaging.


## Objective

The primary goal of this project was to gain a practical understanding of the core systems required to build a first‑person shooter from the ground up. The development process focused on learning how modern FPS games structure their gameplay logic, animation flow, and enemy behavior using Unreal Engine’s built‑in frameworks. Throughout the project, several foundational concepts were explored in depth:

### **State Machines**  
Used to manage character animation states such as idle, walking, running, aiming, shooting, and reloading. The state machine ensures smooth transitions between animations based on player input and gameplay conditions, creating a responsive and believable character controller.

### **Behavior Trees**  
Implemented to drive enemy AI decision‑making. Behavior trees control how android enemies patrol, detect the player, chase targets, take cover, and engage in combat. This system allowed for modular, readable AI logic that can be expanded with additional behaviors.

### **Animation Blueprints**  
Used to synchronize character movement with animation data. This includes blending between locomotion states, handling aim offsets, and coordinating upper‑body animations (like firing) with lower‑body movement. The result is a fluid and reactive animation system that responds directly to gameplay events.

### **Game Design & Feedback Systems**  
Integrated sound cues, particle effects, muzzle flashes, hit impacts, and camera feedback to enhance player immersion. These elements help communicate gameplay events clearly and make combat feel more dynamic and satisfying.


## Installation

1. **Download the Project**
   - Click the green **Code** button at the top of the repository.
   - Select **Download ZIP**.
   - Once the download is complete, extract the ZIP file to a folder of your choice.  
     Make sure the folder path does not contain special characters, as Unreal projects can be sensitive to that.

2. **Open the Project in Unreal Engine**
   - Navigate to the folder where you extracted the project.
   - Locate the `.uproject` file and double‑click it to open the project in **Unreal Engine 5**.
   - Recommended version: **UE 5.0.3 or newer** to ensure compatibility with assets, shaders, and engine features used in this project.
   - If prompted, allow Unreal Engine to **build or update project files**.

3. **Verify Required Plugins & Settings**
   - Ensure that all default Unreal Engine plugins required for FPS templates, animation blueprints, and behavior trees are enabled.
   - If Unreal asks to rebuild missing modules, click **Yes**.

4. **Load Assets & Compile Shaders**
   - The first time you open the project, Unreal may take a few minutes to compile shaders and load assets.
   - Wait for the editor to finish processing before running the game.

5. **Run the Game**
   - Once the project is fully loaded, click **Play** in the Unreal Editor toolbar.
   - The game will start in the default viewport, allowing you to test movement, shooting, and AI behavior.

### Important
You must have **Unreal Engine 5 installed** on your computer to open and run this project.  
Older versions of Unreal Engine may not support certain features used in this project.

