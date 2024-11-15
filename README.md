# Tom & Jerry Image Classification

###
## Model Architecture
- **Base Model**: MobileNet (pre-trained on ImageNet)
- **Additional Layers**:
- `GlobalAveragePooling`
- Fully Connected Layer with 512 units and ReLU activation
- Fully Connected Layer with 256 units and ReLU activation
- Output Layer: Sigmoid activation for binary classification