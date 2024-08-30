
# Vehicle Detection and Counting App

This project is a web application for detecting and counting vehicles in real-time using Python, Flask, OpenCV (cv2), and NumPy. The app processes video streams to identify and count vehicles, providing a user-friendly interface for monitoring traffic.

## Features

- **Real-time Vehicle Detection**: Utilizes OpenCV for detecting vehicles in video streams.
- **Vehicle Counting**: Counts the number of vehicles passing through a predefined area.
- **Web Interface**: Flask-based web application for easy interaction and monitoring.
- **Customizable Parameters**: Adjust detection and counting parameters to suit different environments.

## Requirements

- Python 3.7+
- Flask
- OpenCV (cv2)
- NumPy

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/ChakrabortyJoy/Vehicle-Detection-and-Counting-App.git
    cd vehicle-detection-counting
    ```

2. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Ensure you have the necessary video files and pre-trained models**.

## Usage

1. **Run the Flask app**:
    ```bash
    python app.py
    ```

2. **Open your web browser and go to** `http://127.0.0.1:5000/`.

3. **Start the video feed**: Click the "Start Video" button to begin processing the video stream.

4. **View the vehicle count**: The real-time vehicle count will be displayed on the web page.

## Project Structure

- `app.py`: Main Flask application file.
- `detector.py`: Contains the vehicle detection and counting logic.
- `static/`: Static files (CSS, JavaScript).
- `templates/`: HTML templates for the web interface.
- `requirements.txt`: List of required Python packages.

## Customization

- **Detection Parameters**: Modify the parameters in `detector.py` to adjust the sensitivity and accuracy of vehicle detection.
- **Web Interface**: Customize the HTML and CSS files in the `templates/` and `static/` directories to change the appearance of the web interface.

## Acknowledgements

- OpenCV for providing the tools for image processing and computer vision.
- Flask for the web framework.
- NumPy for numerical operations.

