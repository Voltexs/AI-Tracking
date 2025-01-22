# Real-time Object Detection with YOLOv8

A Python application that performs real-time object detection using YOLOv8 and your computer's webcam. This project can detect and track people and various objects in live video feeds.

---

## Features

- **Real-time object detection** using YOLOv8
- **Webcam integration**
- Live video feed with annotated detections
- Simple and easy-to-use interface

---

## Prerequisites

Before running this project, make sure you have the following installed:

- **Python 3.x**
- **OpenCV (cv2)**
- **Ultralytics YOLOv8**

You can install the required packages using pip:

```bash
pip install ultralytics opencv-python
```

---

## Installation

1. **Clone this repository:**

   ```bash
   git clone <your-repository-url>
   cd <repository-name>
   ```

2. **Download the YOLOv8 model weights:**

   Ensure that `yolov8n.pt` is in the project root directory.

---

## Usage

Run the application using Python:

```bash
python track.py
```

### Controls

- Press **'q'** to quit the application

---

## How It Works

The application:

1. Initializes the YOLOv8 model with pre-trained weights
2. Captures video from your default webcam
3. Processes each frame through the YOLOv8 model
4. Displays the results with bounding boxes and labels in real-time

---

## Project Structure

```
├── track.py          # Main application file
├── yolov8n.pt        # YOLOv8 model weights
└── README.md         # Project documentation
```

---

## Contributing

Feel free to fork this project and submit pull requests. For major changes, please open an issue first to discuss what you would like to change.

---

## License

This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

---

## Acknowledgments

- [Ultralytics YOLOv8](https://github.com/ultralytics/ultralytics)
- OpenCV team
