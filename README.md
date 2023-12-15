# EcoCycle-ML
Capstone project repository for Machine Learning path

this learning model aims for classifying rusts on steel.
using MobileNetV2 as it's base model for a better accuracy and lightweight size 
so this model is fit for our use case because we want to deploy our model into mobile devices using TFLite


MobileNetV2 performances:
| Model    | Size (MB) | Top-1 Accuracy | Top-5 Accuracy | Parameters | Depth | Time (ms) per inference step (CPU) | Time (ms) per inference step (GPU) |
|----------|-----------|----------------|----------------|------------|-------|-----------------------------------|-----------------------------------|
| MobileNetV2 | 14        | 71.3%          | 90.1%          | 3.5M      | 105    | 25.9                             | 3.8                               |

[List of Pre-Trained Model from Keras Api](https://keras.io/api/applications/)


