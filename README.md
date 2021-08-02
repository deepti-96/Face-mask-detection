# FACE MASK DETECTION

## Objective
A Face Mask Detector is developed using Keras, TensorFlow, MobileNet, and OpenCV in this Python programming project. We'll also look at how to do this using a live video camera. These sorts of models might be combined with CCTV cameras in the future to detect and identify persons without masks. There was no morphing masked picture dataset used in the face mask detector. The model is realistic, and because it is based on the MobileNetV2 architecture, it is also computationally efficient, making it easier to deploy to embedded systems (Raspberry Pi, Google Coral, etc.).<br />
As a result, this technology may be utilized in real-time applications that need face-mask detection for safety reasons owing to the Covid-19 outbreak.<br />
This project may be connected with embedded systems and used to guarantee that public safety rules are followed at airports, train stations, offices, schools, and public areas.<br />

![image](https://user-images.githubusercontent.com/72935128/127898629-dda6878a-e052-45f2-92ce-1dacffd2cb56.png)<br />

## Tech-stack/Framework Used
•	OpenCV<br />
•	Keras<br />
•	TensorFlow<br />
•	MobileNetV2<br />

## Considerations
This dataset consists of 3833 images belonging to two classes:<br />
•	with_mask: 1915 images<br />
•	without_mask: 1918 images<br />

The images used were real images of faces wearing masks. The images were collected from the following sources:<br />
•	Google Search API <br />
•	Kaggle datasets<br />
•	RMFD dataset<br />

## Prerequisites
The file requirements.txt contains all the needed dependencies and libraries. <br />

![image](https://user-images.githubusercontent.com/72935128/127898809-2b9bb5ca-cb7c-4768-a33f-7695cad6f1e0.png)<br />

## Final Remarks
We've developed a model that can identify if someone has worn a mask or not. These kinds of models may be deployed in public locations, allowing authorities to readily monitor the situation.<br />


