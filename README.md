# Real-Time Face Mask Detection

This project implements a real-time face mask detection system using pretrained convolutional neural networks (CNN) in ONNX format. It detects faces quickly and classifies whether the person is wearing a mask or not.

## Features

- Fast and accurate face detection using **SCRFD** model  
- Binary classification of mask status with a custom mask classifier  
- Real-time inference pipeline with OpenCV and NumPy  
- Annotates detection results on images with bounding boxes and labels  

## Technologies Used

- Python  
- OpenCV  
- ONNX Runtime  
- SCRFD face detection model  
- Pretrained CNN mask classifier  

## How to Run

1. Clone the repository  
2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the script with an input image:
    ```bash
    python mask_detection.py --input path/to/image.jpg
    ```
4. Output image with detections will be saved in the `output` folder  

## Model Details

- Face detection powered by **SCRFD** (ultra lightweight and fast)  
- Mask classifier trained on custom dataset, exported to ONNX format  

## License

This project is licensed under the MIT License.  

---

© [Your Name]
