# EcoCycle-ML
Capstone project repository for Machine Learning path

this learning model aims for classifying rusts on steel.
using Xception to be compatible with our current deployment method and also having a necessary amount of parameters 
also having a good Top-5 accuracy and smaller size compared to the other similar option.
our model having a good accuracy in about >70% accuracy


Xception performances:
| Model    | Size (MB) | Top-1 Accuracy | Top-5 Accuracy | Parameters | Depth | Time (ms) per inference step (CPU) | Time (ms) per inference step (GPU) |
|----------|-----------|----------------|----------------|------------|-------|-----------------------------------|-----------------------------------|
| Xception | 88        | 79.0%          | 94.5%          | 22.9M      | 81    | 109.4                             | 8.1                               |

[List of Pre-Trained Model from Keras Api](https://keras.io/api/applications/)


