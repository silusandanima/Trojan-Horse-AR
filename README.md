Trojan Horse AR

Project Overview

Trojan Horse AR is a themed WebAR experience developed using A-Frame and AR.js. By pointing a smartphone camera at a Hiro marker, users can explore an augmented reality scene inspired by the ancient city of Troy.

The experience features a Trojan horse, Greek soldiers, and a city fortress, with interactive objects and animations.

Project Links

* Live Website: https://silusandanima.github.io/Trojan-Horse-AR/
* GitHub Repository: https://github.com/silusandanima/Trojan-Horse-AR

Project Information

* Project Name: Trojan Horse AR
* Group Number: Group 5
* Technologies: HTML, CSS, JavaScript, A-Frame, AR.js
* 3D Model Format: GLB
* Tested Device and Browser: Opera Gx, Chrome, google, Phone, laptop

How to Use

1. Open the live website on a smartphone.
2. Allow access to the camera.
3. Display a Hiro marker on another screen or print one.
4. Hold the phone approximately 30–50 cm from the marker.
5. Keep the marker fully visible and in a well-lit area.
6. Tap the objects to explore their interactive features.

Interactive Features

* Trojan Horse: Tap the horse to make it grow or shrink and trigger the Greek soldiers.
* Greek Soldiers: The soldiers move down from the horse towards the ground.
* Golden Ball: Tap the ball to change its colour.
* City of Troy: Tap the city to activate its shaking animation.
* Marker Status Banner: Displays green text when the marker is detected and red text when the marker is lost.

Task Requirements Checklist

No.	Requirement	Implementation
1	Hiro marker scene with four or more objects, two or more primitive types, and an <a-text> label	Includes a ground plane, platform, columns, flagpole, flag, golden ball, and title label.
2	At least two animated objects with different properties	Includes rotation, position movement, and scaling animations.
3	At least one GLTF/GLB model other than the workshop duck	Includes Trojan horse, Greek soldier, and city models.
4	Ball colour change and one additional tappable object	The golden ball changes colour and other objects have custom interactions.
5	Marker status banner	Changes text and colour when the Hiro marker is found or lost.
6	HTTPS hosting and phone testing	Hosted through GitHub Pages. Phone testing details should be completed above.

Custom Components

The project uses custom JavaScript components:

* grow-toggle – Makes the Trojan horse grow or shrink and triggers the soldiers.
* soldier-drop – Controls the soldiers’ movement from the horse to the ground.
* temple-quake – Creates a shaking animation for the city.
* tap-picker – Helps detect taps on objects in the AR scene.
* safe-model – Loads GLB models and displays a fallback shape if a model fails to load.
* marker-banner – Updates the status banner when the Hiro marker is detected or lost.
* color-changer – Changes the colour of the golden ball.

3D Models – Credits and Licences

The project uses the following 3D models:

Model	Project File	Source
Trojan Horse	assets/models/trojan-horse.glb	Hyper3D Rodin
Greek Soldier	assets/models/greek-soldier.glb	Hyper3D Rodin
City of Troy / Fortress	assets/models/temple.glb	https://hyper3d.ai/workspace/rodin/a9e59773-d8ab-4ec9-ab12-a64124e97b06

Licence Information: The models are identified as generated using Hyper3D Rodin. The applicable export and usage licence terms must be checked against Hyper3D’s current terms before submission. Add the exact licence wording and the date checked here.

Libraries and Technologies

* A-Frame 1.6.0 – Used to create the 3D scene.
    https://aframe.io/
* AR.js 3.4.7 – Used for marker-based augmented reality.
    https://github.com/AR-js-org/AR.js
* HTML, CSS, and JavaScript – Used to build and control the experience.

Project Folder Structure

Trojan-Horse-AR/
│
├── index.html
├── README.md
│
└── assets/
    ├── images/
    │   └── ground.jpg
    │
    └── models/
        ├── trojan-horse.glb
        ├── greek-soldier.glb
        └── temple.glb

Run Locally

1. Clone or download the GitHub repository.
2. Open the project folder in Visual Studio Code.
3. Install the Live Server extension.
4. Right-click index.html.
5. Select Open with Live Server.
6. Allow camera access and display a Hiro marker.

The camera requires HTTPS or localhost. Opening the HTML file directly may not allow camera access.

Troubleshooting

* Black screen: Check camera permissions and use the HTTPS live website.
* Nothing appears: Ensure the Hiro marker is fully visible, flat, and well lit.
* Fallback shape instead of a model: Check that the GLB file exists and that its filename and path match the HTML code.
* Camera does not start: Check browser camera permissions or try another supported browser.

Author

Created as a group WebAR project for a university assignment.

Project Name: Trojan Horse AR
Group Number: Group 5
