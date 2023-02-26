## Tamil Isolated Sign Language Recognition
 
This is a Python Flask web application that uses computer vision to recognize isolated sign language gestures in Tamil language. The application uses OpenCV for image processing and the CVZone library for hand detection and gesture classification.
 
### Prerequisites
To run the application, you will need:
- Python 3.6 or later
- Flask (`pip install flask`)
- OpenCV (`pip install opencv-python`)
- CVZone (`pip install cvzone`)
 
### Usage
To start the application, run `python app.py` in the terminal and then go to http://localhost:5000 in your web browser. Once you are on the main page, click the "Start Capturing" button to start the video stream and see the real-time recognition of sign language gestures.
 
### Features
The application can recognize the following Tamil sign language gestures:
- Thanks
- Amma (mother)
- Sorry
- Water
- Good
- Bud (friend)
- Anna (brother)
- Akka (sister)
 
To recognize a gesture, you need to perform it in front of a camera. The application will detect your hand and crop the image to the region of interest. Then, it will resize the cropped image to a fixed size (300x300 pixels) and feed it to a pre-trained deep learning model that will classify the gesture.
 
### Acknowledgements
The pre-trained model used in this application was trained on the Tamil Sign Language Dataset, which was created by the Center for Language Technology and Computing at Anna University, Chennai. The dataset is available for research purposes at https://www.clta.in/tsl_dataset.html. The CVZone library was created by Murtaza Hassan and is available at https://github.com/codewithharry/cvzone.
 

 