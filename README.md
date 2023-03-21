# <center>DRISHTI</center>
___

## Content

- [Comparative Analysis](#analysis)
- [Steps](#steps)
- [MxNet](#mx)
- [MTCNN](#mt)
- [ArcFace](arc)
- [Use Case](#usecase)


Drishti a FRT(Face Recognition technology) used to identify people is developed on Mxnet deep learning framework and applies MTCNN for face detection and ArcFace for face recognition.

<a name = 'analysis'></a>
## Comparative Analysis:
The combination of MxNet, MTCNN and ArcFace gives us edge in following ways:

- Real time face Recognition
- Works in dim lighting, occlusion and different orientation
- Low false positive rate
- Distinguishing information from faces even under difficult situations
- Able to identify faces with/without mask and glasses on a single train photo capture.

<a name = 'steps'></a>
## Steps:

1) Live camera intake
2) Face Detection through mtcnn
3) Face Embedding 
4) Training Mxnet customized model
5) Saving the model and embeddings
6) Predicting the face through the model


<img src = 'https://www.starlinkindia.com/blog/wp-content/uploads/2019/05/Biometrics-Face-Recognition-How-Does-it-work.jpg' style = 'display: block;width:300px;display: block; margin-left: auto; margin-right: auto;'></img>

<a name = 'mx'></a>
## MxNet:
The subject of face recognition has made substantial use of the potent deep learning framework MXNet. MXNet's versatility and scalability, which enable it to easily handle big datasets and complex models, are among its key features.MXNet is a great option for real-time face recognition applications due to its excellent performance and effective memory utilisation. 

<a name = 'mt'></a>
## MTCNN

The Multi-Task Cascaded Convolutional Neural Network (MTCNN) has a number of advantages over conventional face identification methods, including:



1. High accuracy: It has been demonstrated that MTCNN can detect faces with high accuracy rates, even in difficult situations like dim lighting, occlusion, or different orientations.


2. Versatility: MTCNN is more versatile than other models since it can detect faces at various scales and orientations.


3. Speed: MTCNN is quick and effective, making it appropriate for real-time applications like live streaming or video surveillance.


4. MTCNN is capable of carrying out numerous tasks at once, including face alignment, facial landmark detection, and face detection.


5. Low false positive rate: Because of MTCNN's low false positive rate, it is less likely to mistakenly identify non-faces as faces.

<a name = 'arc'></a>
## ArcFace
<img src = 'https://learnopencv.com/wp-content/uploads/2020/07/arcface.jpg' style = 'display:block;'></img>

- Good accuracy while handling large-scale face recognition datasets.

- ArcFace performs at the cutting edge on benchmark datasets including LFW, MegaFace, and IJB-C.


- Appropriate for applications like access control and video surveillance.

- The resilient algorithm can adapt to changes in illumination, position, and expression.

- Extracts distinguishing information from faces even under difficult situations.

<a name = 'usecase'></a>
## Use Case:

Face Recognition Technology in Security

Steps:

- Creating a proper dataset for photos with description
  eg. aadhar card photos government dataset
- Training our model on the existing dataset. Incase new registry add the photo to datasett and train the model.
- The authorities have the access to live feed from public cameras.
- With help of FRT model identify/locate the criminal from videos.
- Authorities can also take help from social media photos to narrow down the search.

