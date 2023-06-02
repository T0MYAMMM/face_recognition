# Face Recognition

Face Recognition is a Python application that uses computer vision techniques to recognize faces in real-time using a webcam.

## Features

- Real-time face recognition
- Displays annotated frames with recognized faces
- Calculates confidence levels for face matches
- Supports adding known faces for recognition

## Requirements

- Python 3.x
- OpenCV
- Numpy
- face_recognition

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/face-recognition.git

2. Install the required dependencies:

   ```bash
    pip install opencv-python numpy face-recognition
  
## Usage

1. Place the face images of known individuals in the faces directory.

2. Run the script:
   ```bash
   python main.py
  
3. The application will open a window showing the webcam feed with face recognition annotations.

4. Press 'q' to exit the application.

Customization
Adjust the face_match_threshold parameter in the face_confidence function to control the sensitivity of face matching.

Customize the display annotations by modifying the code in the run_recognition method.

Contributing
Contributions are welcome! If you have any ideas, suggestions, or improvements, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Feel free to modify and customize it to fit your project's specific details and requirements.

  
