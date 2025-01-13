# Plinko Physics Simulator
The Plinko Physics Simulator is a web-based interactive simulation that models the behavior of particles falling through a triangular grid of pegs. Inspired by the classic “Plinko” game from “The Price Is Right,” this simulator allows users to visually explore the randomness and probability of particle distribution based on various parameters such as gravity, the number of particles, and the peg layout.

Built using p5.js for rendering graphics and Matter.js for physics simulations, this tool provides a hands-on approach to understanding physics concepts like gravity, collision detection, and random processes. It can be used as an educational tool for demonstrating how seemingly random events can form patterns, making it an ideal resource for learning about probability and the dynamics of particles.

Features

1. Interactive Simulation
	•	Watch particles fall through a triangular grid of pegs, bouncing off each peg and eventually landing in one of several bins at the bottom.
	•	Customize the simulation by adjusting parameters like the number of particles, gravity, and peg layout.
	•	See the statistical distribution of particles after many iterations, providing a visual representation of probability.

2. Realistic Physics
	•	The simulator uses the Matter.js physics engine to handle particle collisions, gravity, and motion, providing an accurate simulation of the real-world behavior of particles.
	•	The interactions between particles and pegs are governed by realistic physics, making the simulation both visually appealing and scientifically accurate.

3. Visual Representation of Randomness
	•	The distribution of particles as they fall through the pegs shows the phenomenon of randomness converging into a predictable pattern after many trials.
	•	This can be used to demonstrate how random processes like the Central Limit Theorem work in real-world situations, showing the formation of a normal distribution or bell curve.

4. Customizable Settings
	•	Gravity: Adjust the gravity to see how it affects the movement of the particles.
	•	Number of Particles: Change the number of particles falling through the grid to see how large-scale behavior is affected.
	•	Peg Layout: Customize the arrangement of pegs to explore how different configurations impact the particle distribution.

5. Educational Tool
	•	Perfect for classrooms, science demonstrations, or self-study, the simulator provides an interactive way to explore concepts like probability, gravity, and collisions in physics.
	•	It can be used to discuss how random processes lead to predictable patterns, making it an excellent visual aid for understanding statistical concepts.

How to Run

To run the Plinko Physics Simulator on your local machine:
	1.	Clone the repository:

git clone https://github.com/MaanavKrishna/Plinko-Physics-Simulator.git


	2.	Navigate to the project directory:

cd Plinko-Physics-Simulator


	3.	Open the index.html file in any modern web browser to start the simulation.

File Structure
	•	index.html: The main HTML file that serves as the entry point for the application.
	•	style.css: Contains the styles for the user interface and simulation layout.
	•	sketch.js: The main JavaScript file containing the logic for setting up and controlling the p5.js simulation.
	•	Ground.js, Divisions.js, Particle.js, Plinko.js: Supporting JavaScript files defining the behavior of objects in the simulation (e.g., particles, pegs, and divisions).
	•	matter.js: The physics engine used for simulating realistic particle interactions.

Technologies Used
	•	p5.js: A JavaScript library for creative coding that simplifies the process of drawing graphics and handling animations.
	•	Matter.js: A 2D physics engine that provides collision detection and realistic physics behavior for particles and objects.
	•	HTML5 & CSS3: For structuring and styling the web application.
	•	JavaScript: Used for implementing the core functionality and logic of the simulation.

Enhancements & Future Improvements
	•	Score Tracking: Add a system to track how many particles fall into each bin, providing additional data to users.
	•	Advanced User Controls: Allow users to interact with the simulation more deeply by modifying the layout of the pegs in real time.
	•	Graphs & Data Analysis: Add visual graphs that represent the statistical distribution of particles after each simulation to give users deeper insights into probability and randomness.
	•	Mobile-Friendly UI: Improve the design and responsiveness for mobile devices to ensure the simulator works smoothly on any screen size.
	•	Sound Effects: Add sound effects for particle collisions and interactions to enhance the immersive experience.
	•	Leaderboards: Introduce a feature where users can share their settings and challenge others for a better distribution or higher number of particles.

Contributing

Contributions are welcome! If you have any suggestions, features, or improvements, feel free to fork this repository and submit a pull request. We would love to improve this project with your input!

To contribute:
	1.	Fork the repository.
	2.	Make your changes.
	3.	Create a pull request to the main branch.

License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software as long as you include the original license in your distributions.

Acknowledgements
	•	p5.js: A creative coding library that makes drawing graphics and animations in JavaScript easier.
	•	Matter.js: A physics engine that provides accurate simulations for 2D objects, including collision detection and physics-based motion.
	•	Special thanks to the open-source community for their contributions and tools!

Feel free to modify this README according to any additional features or personal preferences for your project!
