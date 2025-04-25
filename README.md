![Screenshot_20250425_091923_Chrome](https://github.com/user-attachments/assets/d7f885f6-e174-4aa3-b611-96231eeaf430)

# Augmented Reality Object Clicker Website
## Description
A project made at Atlas School Tulsa as a proof-of-concept for my website. It features a rotating, Augmented Reality, 3D carousel that has links to all of my socials. This project is fully browser-based. Full Augmented Reality can be accessed from any device that has a forward-facing camera, although you can access a 2D version of this website on your computer.
### Requirements
 - A-Frame (for AR support)
 - Website is able to be accessed via QR code
 - Contains Augmented Reality objects in scene
 - AR objects must be interactable
 - AR objects must remain in-place relative to the user, even as the user moves about the virtual environment/real-world environment
 - Contains interactable AR links for accessing socials (Github, LinkedIn, etc.)
### Features
- Carousel that will dynamically update it's focus as you move about the room
- Rotates automatically to show all website links without requiring user interaction
- Pop-ups detailing accessible websites

## How to use
To actually open this website, you can scan the QR code found in this repository at:
>ARObjectClicker/tree/main/images/frame.png

You can also access the website [here](https://maximumbloop.github.io/ARObjectClicker/).
### 2D Mode
The website will always be loaded in with 2D view enabled by default. On a PC or Mac, you may move about the scene with the following controls:
 > W (up)
 A (left)
 S (down)
 D (right)
 
 > Mouse movement (freelook)
 Left Click (interact with links)

### AR Mode
To access Augmented Reality mode, simply open the website on any mobile device and tap the **AR** button in the bottom-right corner of your screen. Once loaded, you may move about the room to view the carousel and tap on the carousel objects to open links to each corresponding social. To leave the AR mode, simply go back in your browsing history to the original page.
# Challenges
- Learning the A-Frame framework required learning Three.js, a framework I was previously inexperienced with.
- A-Frame's documentation was rather hard to understand sometimes. Oftentimes the only ways to understand a particular component was to go talk to someone experienced with A-Frame or to parse through the code of the examples on A-Frame's website.
- I had never created a carousel in 2D before, so I had to get creative to build a 3D one in the timeframe allotted.
# Future Development Actions
- Interactability for rotating the whole carousel via touch/click inputs
# Credits
## Developer
### Brad Brown
- [Github](https://github.com/MaximumBloop)
- [LinkedIn](https://www.linkedin.com/in/bradebrown/)
## Tech Stack(s)
- HTML
- CSS
- Javascript
## Frameworks
- [A-Frame](https://aframe.io/)
- [ThreeJS](https://threejs.org/)
#
> Written with [StackEdit](https://stackedit.io/).
