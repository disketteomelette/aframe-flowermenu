# aframe-flowermenu
A-frame cool menu that appears/disappears when user put their controllers together! Created by JC Rueda (github.com/disketteomelette). Licensed under MIT-TAL License (watch my MIT-TAL repository).

## Description
This project leverages **A-Frame**, a framework for creating Virtual Reality (VR) and Augmented Reality (AR) experiences on the web, to implement an interactive **Augmented Reality (AR)** experience. In this case, a 3D object in the shape of a **flower** is deployed with interactions using the user's hands.

When the user enters AR/VR mode using a VR headset, and put their controllers/hands together, a flower-like menu appears in the scene. The flower consists of several interactive buttons that can be hovered over and pressed using the user’s hands (represented by the **left** and **right interaction boxes**).  The flower opens up when the user’s hands come into close proximity or collide, and each button responds to hover and click actions with visual feedback and custom sound effects. The interactive menu is designed to be an example of how to trigger actions and animations based on user input in AR.


## Features
- **Augmented Reality (AR)**: Compatible with WebXR-enabled devices, providing an AR experience where users can interact with objects in a physical space.
- **Hand Interactivity**: Users can interact with the menu using their hands/controllers, represented by **interaction boxes** in the scene (left and right).
- **Flower Animations**: The flower unfolds and contracts with smooth animations, adding dynamism to the experience.
- **Dynamic Sounds**: Custom sounds (e.g., when interacting with the flower or pressing buttons) enhance user immersion.
- **Collision Text**: A HUD displays dynamic text to show information about collisions between the controllers and the flower’s buttons.
- **Button Scaling**: The flower's buttons grow in size when the user approaches them, providing clear visual feedback.

## Technologies Used
- **A-Frame**: A framework for creating VR/AR experiences.
- **WebXR**: An API for immersive web experiences, compatible with AR and VR devices.
- **JavaScript**: Handles the interaction and animation logic.
- **HTML/CSS**: Structures and styles the web page.

## Functionality
1. **Interactive Menu**: Hovering over the flower’s buttons highlights them and allows user interaction.
2. **Animations**: The flower animates to show its unfolding and closing when interacting with the controllers.
3. **Hand Controllers**: Uses the positions of the AR controllers to detect collisions with the flower and its buttons.
4. **Sound Effects**: Custom sounds are played when the user interacts with objects, such as clicks or when the object changes state.
5. **Collision Text**: Provides feedback to the user about what action they are performing (e.g., which button on the flower is being touched).

## Requirements
To run this AR/VR experience, you need a VR compatible headset or a browser with VR emulation plugins. This example has just only tested on **Quest 3**. 
