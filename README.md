# MathwithGesture


This project demonstrates a real-time math problem solver system using computer vision and AI. The system captures webcam input, processes hand gestures, and interacts with a generative AI model to provide responses.

## Requirements
Python 3.x: Ensure Python is installed on your system.

Libraries: You will need to install the following Python libraries:

opencv-python
cvzone
numpy
google-generativeai
Pillow
streamlit

## Set Up Google Generative AI API:

Obtain an API key from Google Generative AI and replace the placeholder in the code with your API key.

## Prepare the Math Gestures Image:

Ensure the image file MathGestures.png is present in the project directory. This image is used as a visual aid on the Streamlit app.

## Running the Project

Start the Streamlit App:

Run the following command to start the Streamlit app:

streamlit run <your-script-name>.py
Replace <your-script-name> with the name of your Python script (e.g., app.py).
Access the App:

Open a web browser and go to http://localhost:8501 to interact with the Streamlit application.

Ensure your webcam is connected and functioning. The application will capture video from the webcam.

**Hand Gestures:**

Perform specific hand gestures to interact with the application:
1. One Finger Up: Draw on the canvas.
2. No Fingers Up: Clear the canvas.
3. All Fingers Up (except thumb): Send the canvas content to the AI model for processing.
   
**AI Response:**

The AI model will analyze the canvas content and generate a response based on the math problem drawn.

**Troubleshooting**
Webcam Not Detected: Ensure your webcam drivers are up-to-date and check if other applications are using the webcam.
Missing Libraries: Ensure all required libraries are installed. Refer to the requirements section for installation instructions.
