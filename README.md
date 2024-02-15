# Driver-Drowsiness-Detection
Driver drowsiness detection is a project built using Dlib and OpenCV with Python as a backend language.
<h3>Logic of project</h3>
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library.
The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which 
we determine whether the eyes are open or they are closed.</br></br>
<center><img src="DDD/Diagrams/facial_landmarks_68markup.jpg" align="center" height="350"></center>
<b>The 68-landmark detector data (.dat) file can be found <a href="[kaggle datasets download -d sergiovirahonda/shape-predictor-68-face-landmarksdat](https://www.kaggle.com/datasets/sergiovirahonda/shape-predictor-68-face-landmarksdat?select=shape_predictor_68_face_landmarks.dat)"> By clicking here</a></B>
<br>
Download the CMake and Vs-code 2022 for dlib  , and setup the Vs code by watching any tutorial video in youtube <a href="https://youtu.be/eaEndTeUiSU?si=A59Tbjx774h1Lf0n" >Click Here</a>
<h3>The working of the project</h3>
<ul><li>As you can see the<b> screenshot </b> where the landmarks are detected using the detector.
<li>Now we are taking the ratio which is described as <i>'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'</i>.
<li>Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.</ul>
<li>It make <i> Alert</i> according to the status of the person </ul>


<b>By Kaushal</b>
