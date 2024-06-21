# Rock-Paper-Scissors
This is an interactive game that uses computer vision to recognize hand gestures and allows users to play against an AI opponent. Developed using Python and OpenCV, the game captures hand gestures via a webcam, interprets them, and determines the winner based on the classic rules of Rock Paper Scissors.

# Features:
1. Real-time Hand Gesture Recognition: The game captures a live video feed from the webcam to recognize hand gestures for rock, paper, and scissors using the OpenCV library and cvzone's HandDetector module.

2. Computer Vision Techniques: The project employs advanced computer vision techniques, such as background subtraction, contour detection, and finger counting, to accurately identify the user's hand gestures. Image processing techniques like resizing, color space conversion, and overlaying images are used to enhance the visual output.

3. Game Logic Implementation: The game follows the standard rules of Rock Paper Scissors: rock beats scissors, scissors beats paper, and paper beats rock. The AI opponent's move is generated randomly to ensure a fair and unpredictable gameplay experience.

4. User Interface: The game provides a visually appealing interface displaying the real-time video feed, the recognized hand gesture, the AI's move, and the current score. The interface is intuitive and easy to use, showing countdowns and results clearly.

5. Feedback and Results: The game gives instant feedback by displaying the outcome of each round on the screen.
A score counter keeps track of the number of wins for both the player and the AI, with the game concluding when either side reaches a score of 3.

# Technical Details:

*Programming Language:* Python
*Libraries Used:* OpenCV, cvzone, NumPy
*Hardware Requirements:* A computer with a webcam
*Image Resources:* Custom images for AI moves and background

# Setup:
-> Ensure the required libraries are installed using pip: # "pip install opencv-python cvzone"
-> Connect a webcam to the computer.
-> Place the image resources in a folder named Resources.

# Conclusion:
This Rock Paper Scissors project showcases the integration of computer vision and gaming, offering a hands-on application of OpenCV and Python. It demonstrates how technology can create interactive and enjoyable user experiences, making it a valuable project for both learning and entertainment purposes.
