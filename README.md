<div align="center"> <h1 align="center"> IBM-Project-1519-1658393990 </div>


<br>
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/IBM_logo.svg" align="center" alt="drawing" width="200" />
  <h2 align="center">A Gesture-based Tool for Sterile Browsing of Radiology Images</h2>
</div>


<p align="center">
  <a href="https://www.python.org/">
    <img src="https://img.shields.io/badge/python-ff2626.svg?style=for-the-badge&logo=python&logoColor=white">
  </a>
  <a href="https://flask.palletsprojects.com/">
    <img src="https://img.shields.io/badge/flask-000000.svg?style=for-the-badge&logo=flask&logoColor=white">
  </a>
  <a href="https://pandas.pydata.org/">
    <img src="https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
  </a>
  <a href="https://www.tensorflow.org/">
    <img src="https://img.shields.io/badge/Tensorflow-ff7626.svg?style=for-the-badge&logo=Tensorflow&logoColor=white">
  </a>
  <a href="https://www.ibm.com/cloud">
    <img src="https://img.shields.io/badge/IBM%20Cloud-990aff?style=for-the-badge&logo=IBM%20Cloud&logoColor=white">
  </a>
</p>
<br>

<h2>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" width="25" height="25" />
  Abstract
</h2>

<p>
  Humans are able to recognize body and sign language easily. 
  This is possible due to the combination of vision and synaptic interactions that were formed along brain development.
  In order to replicate this skill in computers, some problems need to be solved: 
  how to separate objects of interest in images and which image capture technology and classification technique 
  are more appropriate, among others.<br><br>
  In this project Gesture based Desktop automation, First the model is trained pre trained on the images of different hand gestures, 
  such as a showing numbers with fingers as 1 ,2,3,4 . This model uses the integrated webcam to capture the video frame. 
  The image of the gesture captured in the video frame is compared with  the Pre-trained model and the gesture is identified. 
  If the gesture predictes is 1 then images is blurred;2, image is resized;3,image is rotated etc.
<br><br>
  Therefore, this project aims to address these problems and provide a novel handwritten digit recognition system.</p>
<br>

<h2>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" width="25" height="25" />
  Project Objectives
</h2>

<p>

  * Understand the fundamental concepts and techniques of Convolutional Neural Network.
  
  * To gain a broad understanding of image data.
  
  * Learn how to pre-process/clean the data using different data preprocessing techniques.
  
  * Learn how to build a web application using Flask framework.</p>
<br>

<h2>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" width="25" height="25" />
  Project Flow
</h2>

<p>

* User interacts with the UI (User Interface) to upload the image as input

* Depending on the different gesture inputs different operations are applied to the input image.

* Once model analyses the gesture, the prediction with operation applied on image is showcased on the UI.</p>
<br>

<h2>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Star.png" width="25" height="25" />
Prerequisites
</h2>

<p>
    Step 1 : To build this project you have to install : Anaconda navigator 
    <br><br>
    Step 2 : Then you have to Install Python packages
<ul>
  <li> Open anaconda prompt as administrator </li>
  <li> Type “pip install tensorflow” (make sure you are working on python 64 bit) </li>
  <li> Type “pip install opencv-python” </li>
  <li> Type “pip install flask”. </li> </p>
</ul> 
<br>
            

<h2>
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/Fire.png" width="25" height="25" />
   Task and Progress
</h2>

- [x] [Project Design & Planning](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Design%20%26%20Planning)
  - [x] [Ideation Phase](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Design%20%26%20Planning/Ideation%20Phase)
    - [x] [Brainstorm](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Ideation%20Phase/Brainstrom.pdf)
    - [x] [Empathy Map](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Ideation%20Phase/Empathy%20Map.png)
    - [x] [Literature Survey](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Ideation%20Phase/Literature%20Survey.pdf)
    - [x] [Problem Statement](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Ideation%20Phase/Problem%20Statement.pdf)
    - [x] [Use Cases](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Ideation%20Phase/Use%20cases.pdf)
  - [x] [Project Design Phase - I](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20-%20I)
    - [x] [Problem-Solution Fit](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20-%20I/Problem%20Solution%20Fit.pdf)
    - [x] [Proposed Solution](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20-%20I/Proposed%20Solution.pdf)
    - [x] [Solution Architecture](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20-%20I/Solution%20Architecture.pdf)
  - [ ] [Project Design Phase - II](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20-%20II)
    - [x] [Customer Journey Map](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20-%20II/Customer%20Journey%20Map.pdf)
    - [ ] Functional Requirements
    - [ ] Data Flow Diagram 
    - [ ] Technology Architecture
  - [ ] Project Planning Phase
    - [ ] Milestone & Activity List
    - [ ] Sprint Delivery Plan
- [ ] Project Development Phase
  - [ ] Sprint 1
  - [ ] Sprint 2
  - [ ] Sprint 3
  - [ ] Sprint 4
- [ ] Final Project
<br>

<h2> 
  <img src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Travel%20and%20places/High%20Voltage.png" alt="High Voltage" width="25" height="25" /> Assignments 
</h2>

- [x] [Team Lead](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Assignments/Srinath%20(TL))
  - [x] [Assignment 1](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Srinath%20(TL)/Assignment_1_Srinath.ipynb)
  - [x] [Assignment 2](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Srinath%20(TL)/Assignment_2_Srinath.ipynb)
  - [x] [Assignment 3](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Srinath%20(TL)/Assignment_3_Srinath.pdf)
  - [x] [Assignment 4](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Srinath%20(TL)/Assignment_4_Srinath.pdf)
- [x] [Team Member 1](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Assignments/Frahison)
  - [x] [Assignment 1](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Frahison/Assignment_1_Frahison.ipynb)
  - [x] [Assignment 2](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Frahison/Assignment_2_Frahison.ipynb)
  - [x] [Assignment 3](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Frahison/Assignment_3_Frahison.pdf)
  - [x] [Assignment 4](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Frahison/Assignment_4_Frahison.pdf)
- [x] [Team Member 2](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Assignments/Mohanraj)
  - [x] [Assignment 1](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Mohanraj/Assignment_1_Mohanraj.ipynb)
  - [x] [Assignment 2](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Mohanraj/Assignment_2_Mohanraj.ipynb)
  - [x] [Assignment 3](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Mohanraj/Assignment_3_Mohanraj.pdf)
  - [x] [Assignment 4](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Mohanraj/Assignment_4_Mohanraj.pdf)
- [x] [Team Member 3](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Assignments/Srinivasan)
  - [x] [Assignment 1](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Srinivasan/Assignment_1_Srinivasan.ipynb)
  - [x] [Assignment 2](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Srinivasan/Assignment_2_Srinivasan.ipynb)
  - [x] [Assignment 3](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Srinivasan/Assignment_3_Srinivasan.pdf)
  - [x] [Assignment 4](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Srinivasan/Assignment_4_Srinivasan.pdf)
