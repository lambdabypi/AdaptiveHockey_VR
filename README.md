## XR App Vision
Our XR project aims to create an immersive virtual reality (VR) training platform designed specifically for individuals with disabilities who participate in adaptive volt hockey. This application provides a safe, accessible, and engaging environment for athletes to develop both physical and cognitive skills necessary for the sport, regardless of their individual abilities. By offering a virtual space, we aim to familiarize newcomers with the sport through basic movement training while also catering to more advanced users with game scenarios and potential online multiplayer capabilities.

VR breaks the physical limitations of traditional training by providing consistent access to a rink-like environment without requiring specialized equipment or a physical venue. The visual and auditory elements in the XR experience simulate the real-world sensory environment, allowing athletes to build a strong understanding of the game before transitioning into real-world play. With the potential for online play, athletes could practice with others from the comfort of their homes, further enhancing accessibility.

##Prototype
Our current prototype offers a foundational experience for adaptive volt hockey training in VR, combining game mechanics, physical interactions, and realistic player control to create an engaging environment. Below is a breakdown of the key features we have implemented:

### Implemented Features:
* Game Field and Models:

  * Set up a basketball court to serve as the initial game field for volt hockey gameplay.
  * Integrated a volt chair model to replicate the in-game experience, enhancing realism.
* XR Origin Camera Position:

  * Adjusted the XR Origin camera position to provide a first-person view, increasing player immersion.
  * Added a player character model with moving hands to simulate realistic interactions during gameplay.
* Input Configuration:

  * Implemented joystick simulation using the right controller, allowing players to control their movement in-game, similar to a volt chair.
### Physics Setup:

* Added Rigidbody components to key game objects, ensuring realistic physical interactions within the environment.
### Rink and Obstacles:

* Created a rink environment complete with obstacles to simulate a volt hockey scrimmage, allowing players to practice skills and navigate the field.
### User Interactions Enabled:
* Players can freely move their avatars within the VR environment, enabling smooth navigation of the game field.
* Players can interact with the ball using the chair's paddle, mimicking real-world gameplay scenarios.
* Players can practice movement skills by maneuvering through obstacles, improving control and reaction times.
### Future Implementation
* Although the prototype is functional, several improvements are planned for the next phase:

  * The camera does not yet align perfectly with the player's face. Fixing this will improve immersion and create a more realistic experience.
  * Controller mapping and movement mechanics require fine-tuning to enhance smoothness and precision in gameplay.
