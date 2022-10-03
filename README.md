# mini-project-virtual-mouse
ABSTRACT


Gesture-controlled laptops and computers have recently gained a lot of traction. Leap motion is the name for this technique. Waving our hand in front of our computer/laptop allows us to manage certain of its functionalities. Over slides and overheads, computer-based presentations have significant advantages. Audio, video, and even interactive programmes can be used to improve presentations.
 	Unfortunately, employing these techniques is more complicated than using slides or overheads. The speaker must operate various devices with unfamiliar controls (e.g., keyboard, mouse, VCR remote control). In the dark, these devices are difficult to see, and manipulating them causes the presentation to be disrupted. Hand gestures are the most natural and effortless manner of communicating. The camera’s output will be displayed on the monitor. The concept is to use a simple camera instead of a classic or standard mouse to control mouse cursor functions. The Virtual Mouse provides an infrastructure between the user and the system using only a camera. It allows users to interface with machines without the use of mechanical or physical devices, and even control mouse functionalities. This study presents a method for controlling the cursor’s position without the need of any electronic equipment. While actions such as clicking and dragging things will be carried out using various hand gestures. As an input device, the suggested system will just require a webcam. The suggested system will require the use of OpenCV and Python as well as other tools. The camera’s output will be presented on the system’s screen so that the user can further calibrate it.


 











CHAPTER 1
INTRODUCTION
 

1.1	GENERAL INTRODUCTION
A Computer Mouse is an input device that helps to point and to interact with whatever that is being pointed. There are so many types of mouses in the current trend, there’s the mechanical mouse that consists of a single rubber ball which can rotate in any direction and the movement of the pointer is determined by the motion of that rubber ball. Later the mechanical mouse is replaced by the Optical Mouse.
This proposed system is a python application using packages like OpenCV, mediapipe, numpy and autopy. It captures gestures from live video and executes the corresponding actions like clicking, scrolling etc... that’s done by a mechanical mouse

1.2GOAL
The main objective of the proposed AI virtual mouse system is to develop an alternative to the regular and traditional mouse system to perform and control the mouse functions, and this can be achieved with the help of a web camera that captures the hand gestures and hand tip and then processes these frames to perform the particular mouse function such as left click, right click, and scrolling function.

 











CHAPTER 2
LITERATURE SURVEY

 
2.1 STUDY OF SIMILAR WORK
There are some related works carried out on virtual mouse using hand gesture detection by wearing a glove in the hand and also using colour tips in the hands for gesture recognition, but they are no more accurate in mouse functions. The recognition is not so accurate because of wearing gloves; also, the gloves are also not suited for some users, and in some cases, the recognition is not so accurate because of the failure of detection of colour tips. Some efforts have been made for camera-based detection of the hand gesture interface.

2.2EXISISTING SYSTEM
2.2.1 MECHANICAL MOUSE
known as the trackball mouse that is commonly used in the 1990s, the ball within the mouse is supported by two rotating rollers in order to detect the movement made by the ball itself. One roller detects the forward/backward motion while the other detects the left/right motion. The ball within the mouse is steel made that was covered with a layer of hard rubber, so that the detection is more precise. The common functions included are the left/right buttons and a scroll-wheel.
2.2.2 OPTICAL AND LASER MOUSE
A mouse that commonly used in these days, the motions of optical mouse rely on the Light Emitting Diodes (LEDs) to detect movements relative to the underlying surface, while the laser mouse is an optical mouse that uses coherent laser lights. Comparing to its predecessor, which is the mechanical mouse, the optical mouse no longer relies on the rollers to determine its movement, instead it uses an imaging array of photodiodes
2.3 DRAWBACK OF EXISTING SYSTEM
•	Physical mouse is subjected to mechanical wear and tear
•	Physical mouse requires special hardware and surface to operate
•	Physical mouse is not easily adaptable to different environments and its performance varies depending on the environment. 
•	Mouse has limited functions even in present operational environments. 
•	All wired mouse and wireless mouse have its own lifespan 











CHAPTER 3
OVERALL DISCRIPTION
 

3.1 PROPOSED SYSTEM
The proposed AI virtual mouse system can be used to overcome problems in the real world such as situations where there is no space to use a physical mouse and also for the persons who have problems in their hands and are not able to control a physical mouse. Also, amidst of the COVID-19 situation, it is not safe to use the devices by touching them because it may result in a possible situation of spread of the virus by touching the devices, so the proposed AI virtual mouse can be used to overcome these problems since hand gesture and hand Tip detection is used to control the PC mouse functions by using a webcam or a built-in camera.

3.2 FEATURES OF PROPOSED SYSTEM
The AI virtual mouse system is useful for many applications; it can be used to reduce the space for using the physical mouse, and it can be used in situations where we cannot use the physical mouse. The system eliminates the usage of devices, and it improves the human-computer interaction.

3.3 FUNCTIONS OF PROPOSED SYSTEM	
1.  Image capturing
     Python OpenCV library is used to capture the gestures made by user using computers internal camera.
2.processing image
The image captured from the user is analysed and a decision is made what function is to be done according to the gesture shown.

3.4 REQUIREMENTS SPECIFICATION 
1. Accuracy 
The proposed system should be accurate on generating results based on given inputs. 
2. Speed 
The proposed system should be in real time for generating results. 
3. Flexible 
The proposed system should be flexible to new updates and patches in near future. 
 
3.5 FEASIBILITY STUDY
 Feasibility Study in Software Engineering is a study to evaluate feasibility of proposed project or system. Feasibility study is one of stage among important four stages of Software Project Management Process. As name suggests feasibility study is the feasibility analysis or it is a measure of the software product in terms of how much beneficial product development will be for the organization in a practical point of view. Feasibility study is carried out based on many purposes to analyse whether software product will be right in terms of development, implantation, contribution of project to the organization etc. In our proposed system the product is feasibility can be achieved in all four aspects Technical Operational, Economical and Behavioural.

3.5.1 TECHNICAL FEASIBILITY 
In Technical Feasibility current resources both hardware software along with required technology are analysed/assessed to develop project. This technical feasibility study gives report whether there exists correct required resources and technologies which will be used for project development. Along with this, feasibility study also analyses technical skills and capabilities of technical team, existing technology can be used or not, maintenance and upgradation is easy or not for chosen technology etc. In this proposed system technical feasibility is achieved according to above criteria.


3.5.2 OPERATIONAL FEASIBILITY
 In Operational Feasibility degree of providing service to requirements is analysed along with how much easy product will be to operate and maintenance after deployment. Along with this other operational scopes are determining usability of product, determining suggested
solution by software development team is acceptable or not etc. The Operational feasibility can be ensured by the proposed system.

3.5.3 ECONOMICAL FEASIBILITY 
Economic feasibility the most important and frequently used method for evaluating the effectiveness of the proposed system. It is very essential because the main goal of the proposed system is to have economically better results along with increased efficiency. Cost benefit analysis is usually performed for the expected from the proposed system. Since the organization is well equipped with the required hardware, the project was found to be economically feasible and the users who possess a device supports Windows operating system can easily use it.
3.5.4 BEHAVIORAL FEASIBILITY 
The proposed system satisfies behavioural feasibility because the system is providing with good and minimalistic GUI which can easily be understand for any end users and it encapsulates the conversion procedure from the users. Hence, it’s easier to operate the system with ease.


 












CHAPTER 4
OPERATING ENVIRONMENT
 
4.1.1HARDWARE REQUIREMENTS

Computer Desktop or Laptop 
The computer desktop or a laptop will be utilized to run the visual software in order to display what webcam had captured. A notebook which is a small, lightweight and inexpensive laptop computer is proposed to increase mobility. System will be using
 Processor: Core2Duo 
Main Memory: 4GB RAM 
Hard Disk: 320GB 
Display: 14" Monitor

Webcam 
Webcam is utilized for image processing; the webcam will continuously be taking image in order for the program to process the image and find pixel position.
4.1.2 SOFTWARE REQUIREMENTS
OS: Window 7 Ultimate 64-bit 
Language: python, OpenCV
Environment: vscode or PyCharm community edition 2022.2
Documentation: Microsoft word 2010 or higher

4.2TOOLS AND PLATFORMS

PYCHARM
PyCharm is a dedicated Python Integrated Development Environment (IDE) providing a wide range of essential tools for Python developers, tightly integrated to create a convenient environment for productive Python, web, and data science development.


PYTHON 3.7 

Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Its high-level built-in data structures, combined with dynamic typing and dynamic binding, make it very attractive for Rapid Application Development, as well as for use as a scripting or glue language to connect existing components together. Python's simple, easy to learn syntax emphasizes readability and therefore reduces the cost of program maintenance. Python supports modules and packages, which encourages program modularity and code reuse. The Python interpreter and the extensive standard library are available in source or binary form without charge for all major platforms, and can be freely distributed.

OPENCV
OpenCV (Open-Source Computer Vision Library) is an open-source computer vision and machine learning software library. OpenCV was built to provide a common infrastructure for computer vision applications and to accelerate the use of machine perception in the commercial products.
The library has more than 2500 optimized algorithms, which includes a comprehensive set of both classic and state-of-the-art computer vision and machine learning algorithms. These algorithms can be used to detect and recognize faces, identify objects, classify human actions in videos, track camera movements, track moving objects, extract 3D models of objects, produce 3D point clouds from stereo cameras, stitch images together to produce a high resolution image of an entire scene, find similar images from an image database, remove red eyes from images taken using flash, follow eye movements, recognize scenery and establish markers to overlay it with augmented reality, etc.
 
 
MEDIAPIPE
MediaPipe is a framework which is used for applying in a machine learning pipeline, and it is an opensource framework of Google. The MediaPipe framework is useful for cross platform development since the framework is built using the time series data. The MediaPipe framework is multimodal, where this framework can be applied to various audios and videos. The MediaPipe framework is used by the developer for building and analysing the systems through graphs, and it also been used for developing the systems for the application purpose. The steps involved in the system that uses MediaPipe are carried out in the pipeline configuration. The pipeline created can run in various platforms allowing scalability in mobile and desktops. The MediaPipe framework is based on three fundamental parts; they are performance evaluation, framework for retrieving sensor data, and a collection of components which are called calculators, and they are reusable.

NumPy
NumPy is a Python library used for working with arrays. It also has functions for working in domain of linear algebra, Fourier transform, and matrices. NumPy was created in 2005 by Travis Oliphant.

AutoPy
AutoPy is a simple, cross-platform GUI automation library for Python. It includes functions for controlling the keyboard and mouse, finding colours and bitmaps on-screen, and displaying alerts. Currently supported on macOS, Windows, and X11 with the XTest extension.


 



