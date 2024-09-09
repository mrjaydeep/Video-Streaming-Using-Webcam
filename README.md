#Video-Streaming-Using-Webcam
Real-Time Video Streaming with Flask and OpenCV
This project demonstrates how to capture real-time video from your system’s camera using OpenCV and stream it to a web page using Flask. It leverages the power of Flask's lightweight framework to build a web application that serves a live video stream over the network.

## Key Features
- Captures real-time video using OpenCV (`cv2.VideoCapture()`).
- Encodes video frames in JPEG format for efficient transmission.
- Streams video frames to a web page using Flask's `Response` object.
- Implements video streaming via the HTTP `multipart/x-mixed-replace` content type, allowing continuous frame updates without refreshing the page.
- Simple web interface to view the live video feed.

## Technologies Used
- **Flask**: Python micro web framework for creating the web server.
- **OpenCV**: Computer vision library used to capture video and process frames.
- **HTML**: Used for the frontend interface (`index1.html`).
