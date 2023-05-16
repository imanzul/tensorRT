# 🔗 Tensorflow TensorRT YOLOv8

### 1) What is TensorRT ❓
- An optimization tool specifically designed for deep learning inference on GPUs.

### 2) The idea 💡
- TensorFlow acts as the framework for training and preparing the YOLOv8 model.
- Optimizing the model for inference using TensorRT.

### 3) High-level process overview ⏫
#### _Pre-requisite: YOLOv8 model has been trained on a labeled data_
- Conversion: YOLOv8 needs to be converted to a format compatible with TensorRT. TensorRT provides tools for converting YOLOv8 model into an optimized format for inference.
- Optimization: Use TensorRT to optimize the YOLOv8 model for inference on GPU devices.
> Additional information: TensorRT performs various optimizations, such as layer fusion, precision calibration, and tensor memory management, to improve the model's inference speed and efficiency.
- Inference: After that, the YOLOv8 model can be deployed for inference. It involves running the optimized model on input data to detect and classify objects in real-time.

### 4) 
