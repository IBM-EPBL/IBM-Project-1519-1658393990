<div align="center"> <h1 align="center"> IBM-Project-1519-1658393990 </div>


<br>
<div align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/IBM_logo.svg" align="center" alt="drawing" width="200" />
  <h2 align="center"> A Gesture-based Tool for Sterile Browsing of Radiology Images </h2>
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

<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture color[RGB]{168,109,156}> TEAM : </h2></div>

<ol>
  &nbsp; <li> Srinath S [TL]      -  312019205036 </li>    
  &nbsp; <li> Frahison T [TM1]    -  312019205003 </li> 
  &nbsp; <li> Mohanraj A [TM2]    -  312019205016 </li>
  &nbsp; <li> Srinivasan M [TM3]  -  312019205037 </li>
</ol>
<br>

<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture color[RGB]{168,109,156}> INTRODUCTION : </h2></div>

<p>
   <ul> ⦿ Humans are able to recognize body and sign language easily. This is possible due to the combination of vision and synaptic interactions 
           that were formed along brain development. In order to replicate this skill in computers, some problems need to be solved: how to separate objects 
           of interest in images and which image capture technology and classification technique are more appropriate, among others.  </ul>

   <ul> ⦿ In this project Gesture based Desktop automation, First the model is trained pre trained on the images of different hand gestures, 
          such as a showing number with fingers as 1 ,2,3,4. This model uses the integrated webcam to capture the video frame. The image of the gesture captured 
         in the video frame is compared with the pre-trained model and the gesture is identified. 
    If the gesture predicts is 1; then images are blurred; 2, image is resized; 3, image is rotated etc.
 </ul> </p>
<br>

<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture color[RGB]{168,109,156}> PROJECT OBJECTIVE : </h2></div>

<p>
<ul> ➼ Understand the fundamental concepts and techniques of Convolutional Neural Network. </ul>

<ul> ➼ To gain a broad understanding of image data. </ul>

<ul> ➼ Learn how to pre-process/clean the data using different data preprocessing techniques. </ul>

<ul> ➼ Learn how to build a web application using Flask framework. </ul> </p>
<br>

<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture color[RGB]{168,109,156}> PROJECT FLOW : </h2></div>

<p>

<ul> &nbsp; &nbsp; ⦿ User interacts with the UI (User Interface) to upload the image as input. </ul>

<ul> &nbsp; &nbsp; ⦿ Depending on the different gesture inputs different operations are applied to the input image. </ul>

<ul> &nbsp; &nbsp; ⦿ Once model analyses the gesture, the prediction with operation applied on image is showcased on the UI. </ul>

<b> To accomplish this, we have to complete all the activities and tasks listed below : </b>

<ul> ➼ Data Collection. </ul>

<ul> &nbsp; &nbsp; ⦿ Collect the dataset or Create the dataset. </ul>

<ul> ➼ Data Preprocessing. </ul>

<ul> &nbsp; &nbsp; ⦿ Import the ImageDataGenerator library. </ul>
<ul> &nbsp; &nbsp; ⦿ Configure ImageDataGenerator class. </ul>
<ul> &nbsp; &nbsp; ⦿ Apply ImageDataGenerator functionality to Trainset and Testset. </ul>

<ul> ➼ Model Building. </ul>

<ul> &nbsp; &nbsp; ⦿ Import the model building Libraries. </ul> 
<ul> &nbsp; &nbsp; ⦿ Initializing the model. </ul>
<ul> &nbsp; &nbsp; ⦿ Adding Input Layer. </ul>
<ul> &nbsp; &nbsp; ⦿ Adding Hidden Layer. </ul>
<ul> &nbsp; &nbsp; ⦿ Adding Output Layer. </ul>
<ul> &nbsp; &nbsp; ⦿ Configure the Learning Process. </ul>
<ul> &nbsp; &nbsp; ⦿ Training and testing the model. </ul>
<ul> &nbsp; &nbsp; ⦿ Save the Model. </ul>

<ul> ➼ Application Building. </ul>

<ul> &nbsp; &nbsp; ⦿ Create an HTML file. </ul>
<ul> &nbsp; &nbsp; ⦿ Build Python Code. </ul>
<br>

<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture color[RGB]{168,109,156}> PROJECT STRUCTURE : </h2></div>

<b> Create a Project folder which contains files as shown below : </b>


![image](https://user-images.githubusercontent.com/70817219/194914420-9ef53158-9413-447b-a7f3-846d5ed567cb.png)

<ul> &nbsp; &nbsp; ⦿ Dataset folder contains the training and testing images for training our model. </ul>
<ul> &nbsp; &nbsp; ⦿ We are building a Flask Application which needs  HTML pages stored in the templates folder and a python script app.py for server side scripting. </ul>
<ul> &nbsp; &nbsp; ⦿ we need the model which is saved and the saved model in this content is gesture.h5 </ul>
<ul> &nbsp; &nbsp; ⦿ The static folder will contain js and css files. </ul>
<ul> &nbsp; &nbsp; ⦿ Whenever we upload a image to predict, that images is saved in uploads folder. </ul>
<br>

<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture color[RGB]{168,109,156}> TECHNICAL ARCHITECTURE : </h2></div>

![image](https://user-images.githubusercontent.com/70817219/194914841-4fc230f1-53f9-4b5a-8d9a-e902d9fc3581.png)
<br>

<div>
 <h2><picture>
  <source srcset="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.webp" type="image/webp">
  <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f31f/512.gif" alt="🌟" width="32" height="32">
</picture color[RGB]{168,109,156}> Prerequisites : </h2></div>

<p>
    Step 1 : To build this project you have to install : Anaconda navigator 
    <br><br>
    Step 2 : Then you have to Install Python packages

<ul> &nbsp; &nbsp; ⦿ Open anaconda prompt as administrator </ul>
<ul> &nbsp; &nbsp; ⦿ Type “pip install tensorflow” (make sure you are working on python 64 bit) </ul>
<ul> &nbsp; &nbsp; ⦿ Type “pip install opencv-python” </ul>
<ul> &nbsp; &nbsp; ⦿ Type “pip install flask”. </ul> </p>
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
  - [x] [Project Design Phase - II](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20-%20II)
    - [x] [Customer Journey Map](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20-%20II/Customer%20Journey%20Map.pdf)
    - [x] [Functional Requirements](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20-%20II/Functional%20Requirements.pdf)
    - [x] [Data Flow Diagram](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20-%20II/Data%20Flow%20Diagram.pdf)
    - [x] [Technology Architecture](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Project%20Design%20Phase%20-%20II/Technology%20Architecture.pdf)
  - [x] [Project Planning Phase](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Design%20%26%20Planning/Project%20Planning)
    - [x] [Milestone & Activity List](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Project%20Planning/Milestone%20and%20Activity%20List.pdf)
    - [x] [Sprint Delivery Plan](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Project%20Design%20%26%20Planning/Project%20Planning/Sprint%20Delivery%20Plan.pdf)
- [x] [Project Development Phase](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Development%20Phase)
  - [x] [Sprint 1](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Development%20Phase/Sprint%201)
      - [x] [Dataset](https://drive.google.com/file/d/1-5WBhePgSbYiODSiYdiBE1xYvl6z-Iu0/view?usp=sharing)
  - [x] [Sprint 2](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Development%20Phase/Sprint%202)
  - [x] [Sprint 3](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Development%20Phase/Sprint%203)
  - [x] [Sprint 4](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Development%20Phase/Sprint%204)
  - [x] [Testing](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Project%20Development%20Phase/Testing)
- [x] [Final Deliverables](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Final%20Deliverables)
  - [x] [Final Code](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Final%20Deliverables/Final%20Code)
  - [x] [IBM Cloud Deployment](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Final%20Deliverables/IBM%20Cloud%20Deployment)
  - [x] [Project Demonstration](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Final%20Deliverables/Project%20Demonstration)
  - [x] [Project Report](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/tree/main/Final%20Deliverables/Project%20Report)
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
  - [x] [Assignment 2](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Srinivasan/Assignment_2_Srinivasan.pdf)
  - [x] [Assignment 3](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Srinivasan/Assignment_3_Srinivasan.pdf)
  - [x] [Assignment 4](https://github.com/IBM-EPBL/IBM-Project-1519-1658393990/blob/main/Assignments/Srinivasan/Assignment_4_Srinivasan.pdf)
