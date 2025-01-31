# Real-Time Fall Detection

A robust, IoT-based fall detection system utilizing YOLOv11 and ESP32-CAM for real-time monitoring in multi-person environments. This project captures image streams from ESP32, processes them server-side with Python, and uses advanced detection algorithms to identify falls accurately. With real-time streaming and analysis, the system is well-suited for continuous monitoring in healthcare, eldercare, and security applications, ensuring efficient incident detection and response.
## Project Description

This system is designed to detect falls by capturing and analyzing live images transmitted from ESP32 to a server, leveraging the YOLOv11 object detection model. Unlike traditional pose-specific models, YOLOv11 excels in recognizing multiple individuals simultaneously, enhancing the accuracy of fall detection in crowded environments.

Key components of the project:
- **ESP32**: Streams image data over Wi-Fi to a server for processing.
- **YOLO**: Employs the `ultralytics` YOLOv11 model to detect and assess activity, allowing accurate identification of falls within the frame.
- **Python**: Manages image retrieval, fall detection algorithms, and data handling.
- **Flask**: Hosts a web interface for easy access to live monitoring and system outputs.
- **Multithreading**: Ensures seamless operation by handling tasks like data streaming, fall detection, and web service delivery concurrently.

This system combines edge computing with advanced detection algorithms to deliver efficient and reliable fall detection. Its capability to monitor multiple subjects simultaneously enhances safety in healthcare and residential settings, significantly improving response times and reducing fall-related risks.
## Requirements

To run this project, you will need the following hardware and software:

### Hardware:
- **ESP32**: Used for capturing and streaming images over Wi-Fi.
- **Camera Module**: Integrated with the ESP32 to capture live images.
- **Computer or Server**: Running Python for image processing and fall detection.

### Software:
- **Python 3.x**: Make sure Python 3.x is installed on your system.
- **ESP32 Camera Library**: The appropriate library and setup to capture and stream images from the ESP32.
