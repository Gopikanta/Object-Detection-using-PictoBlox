# Object-Detection-using-PictoBlox
Object Detection in PictoBlox using Tobi AI . It detects objects through the webcam and displays the name of the detected object in a speech bubble. A yellow box (sprite) moves along with the detected object’s position, making it easy to visualize. 
Abstract:


This project presents an interactive real-time object detection system built using PictoBlox, a block-based graphical programming environment. By leveraging the Tobi AI extension, the system captures video feed from the webcam, analyzes frames to detect objects, and visually and verbally identifies them on screen. This project is aimed at introducing the concepts of computer vision and artificial intelligence to students in an intuitive and beginner-friendly manner.


Objectives:
To develop a visual system capable of detecting real-world objects using a webcam.
To dynamically display object position, size, and classification using graphical elements (sprites).
To create a voice-feedback mechanism that reads out detected object classes.
To familiarize learners with the fundamentals of AI and object detection through PictoBlox.

Motivation:
With AI and machine learning becoming integral to modern computing, there is a growing need to introduce these technologies in accessible ways. PictoBlox bridges this gap by allowing young learners and beginners to create intelligent systems without coding syntax. This project aims to demonstrate the practicality of AI in a simple visual format.

Tools and Technologies Used:


Tool/Technology
Description
PictoBlox
Graphical coding platform based on Scratch
Tobi AI Extension
AI-powered object detection engine integrated into PictoBlox
Webcam
Captures real-time video feed for object recognition
Speech Block
Converts detected object class to speech output






How Can You Tell?
In your shared screenshot, you are using blocks like:
analyse image from camera
get # of objects
x position of object
class of object


These blocks are part of the Tobi AI extension in PictoBlox.

 What Does the Tobi AI Extension Do Here?
analyse image from camera → Sends the webcam image to the cloud for analysis.
get # of objects → Checks how many objects were detected.
x/y position of object → Gives the coordinates of the detected object.
class of object → Tells you what kind of object it is (e.g., person, cup, bottle).


These are Tobi AI blocks, not standard PictoBlox blocks — so yes, you’re definitely using the Tobi AI extension.









System Design and Workflow:
Workflow:
Start Trigger: The program starts on clicking the green flag.
Camera Activation: Turns on the webcam or laptop camera  with full visibility on the stage.
Image Analysis Loop:


Continuously analyzes frames from the camera.
Checks for detected objects using the Tobi AI model.


Object Detected?:


Yes:
Move a sprite (yellow box) to the object’s X and Y coordinates.
Resize the sprite to match the detected object’s width.
Use text-to-speech to say the object’s class (e.g., "person", "bottle").
No:
Display the message: “No object detected.”


Stop Trigger: Pressing the space key turns off the camera feed.
Space Key Pressed:
Turns off the webcam feed and stops the detection process.

