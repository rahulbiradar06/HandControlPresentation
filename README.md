# HandControlPresentation

HandControlPresentation is a gesture-controlled PowerPoint presentation tool using OpenCV, CVZone, and MediaPipe. This project allows you to navigate through your presentation slides using simple hand gestures, making your presentations more interactive and engaging.

## Features
- **Hand Detection and Tracking**: Utilizes MediaPipe for real-time hand detection and tracking.
- **Gesture Recognition**: Recognizes specific hand gestures to control slide navigation.
- **Seamless Integration**: Integrates with OpenCV for video processing and CVZone for simplifying hand gesture recognition.



## Installation
1. Clone the repository:
    ```bash
    git clone https://github.com/rahulbiradar06/HandControlPresentation.git
    ```
2. Navigate to the project directory:
    ```bash
    cd HandControlPresentation
    ```
3. Install the required packages:
   - Python 3.x
  - OpenCV
  - CVZone
  - MediaPipe
   

## Usage
1. Connect your webcam or ensure your video input device is set up.
2. Run the main script:
    ```bash
    python main.py
    ```
3. Use the following gestures to control your PowerPoint slides:
    - **show pinky finger with while making your fist**: Move to the left slide
    - **show thumb finger while making your  fist**: Move to the right slide
    - **show index finger**: you can draw on presentation
    - **show show index + middle finger**: together it will just show the pointer on the screen which you can hover
    - **show index + middle + ring finger**: it will do undo for whatever you wrote on the slide
    
## How It Works
- **Hand Detection**: Uses MediaPipe's hand detection module to detect and track hand landmarks.
- **Gesture Recognition**: CVZone simplifies the recognition of hand gestures based on the detected landmarks.
- **Slide Control**: The recognized gestures are mapped to PowerPoint slide navigation commands.

## Requirements
- Python 3.x
- OpenCV
- CVZone
- MediaPipe

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## Contact
For any questions or suggestions, feel free to reach out to rahulbiradar0601@gmail.com.

