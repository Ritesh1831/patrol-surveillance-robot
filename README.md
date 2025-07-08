# patrol-surveillance-robot

---
This project implements a robust real-time object detection system for surveillance and patrol robots using YOLOv4-tiny and fallback models like MobileNet SSD and Haar Cascades. Designed for high accuracy, speed, and fail-safe operation in dynamic environments.

---


## 🔍 Key Features

- **Multi-model Detection:**  
  Integrates YOLOv4-tiny with fallback options (MobileNet SSD and Haar Cascades) for uninterrupted detection across real-world conditions.

- **Real-time Performance:**  
  Detects and tracks over **80+ object classes** from the COCO dataset (including humans, vehicles, animals) using OpenCV DNN with minimal latency.

- **Robust Failover Logic:**  
  Automatically switches between models when primary model download or connectivity fails, ensuring continuous object detection.
