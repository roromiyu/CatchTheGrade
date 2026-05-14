# CatchTheGrade

CatchTheGrades
A Dynamic 2D Educational Arcade Experience

📝 Overview
CatchTheGrades is an interactive, fast-paced arcade game developed using the Godot 4 Engine. Designed with a focus on fluid mechanics and real-time feedback, the game challenges players to manage their "Academic Standing" by collecting high-tier grades while navigating the risks of failing marks. It serves as a demonstration of 2D physics, signal-based event handling, and dynamic UI scaling in GDScript.

🕹️ Gameplay Mechanics
Precision Movement: Controlled using standard keyboard inputs (Arrow Keys/WASD), the player maneuvers a collection basket to intercept falling objects.

The Grading System:

High Honors (A & B): Increases total score significantly.

Passing Marks (C & D): Provides marginal score increases.

Failing Marks (F): Deducts points from the player's current standing.

Audio Triggers: High-fidelity audio feedback (Oops.ogg) is utilized to signal "missed" opportunities when a grade bypasses the player and exits the play area.

Live Rank Projection: The on-screen UI dynamically calculates the player’s overall letter grade (from F to A) based on real-time score thresholds.

🛠️ Technical Specifications
Engine: Godot 4.x

Language: GDScript

Platform: Web (HTML5/WebAssembly)

Key Programming Concepts:

Group Management: Utilizes Godot "Groups" to identify falling instances and trigger floor-collision logic.

Randomization Algorithms: Employs randf_range and array mapping to ensure unique gameplay sessions.

Scene Instantiation: Dynamically spawns "Grade" scenes at runtime to manage memory efficiently.

📂 Installation & Deployment
To view the source logic or run the project locally:

Download the repository containing the project.godot file.

Import the project into Godot 4.x.

Ensure all audio assets (CatchSound, MissSound) are mapped correctly in the Inspector.

Press F5 to initialize the debug build.

👤 Developer Credits
Lead Developer: [Your Name]

Project Context: Developed for [Competition Name/Institution Name]

Built with: Godot Engine (Open Source)
