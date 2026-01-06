# CVPR Final Assignments

Complete Computer Vision and Pattern Recognition assignments with face recognition implementation.

## 📁 Folder Structure

```
Final_CVPR_Assignments/
├── Assignment 1/
│   └── MNIST_Digit_Classification_using_NN_.ipynb
│       - Basic neural network for MNIST digit classification
│
├── Assignment 2/
│   ├── 1_Data_Preprocessing.ipynb       # Face detection & preprocessing
│   └── 2_Model_Training.ipynb           # CNN model training
│
└── Assignment 3/
    └── Face_Recognition_Transfer_Learning.ipynb
        - Transfer learning with VGG16, ResNet50, MobileNetV2
```

## 🎯 Assignment Descriptions

### Assignment 1: MNIST Digit Classification
- Basic neural network implementation
- Handwritten digit recognition (0-9)
- Training and evaluation on MNIST dataset

### Assignment 2: Face Recognition Data Preprocessing & Training

1. **Data Preprocessing** (`1_Data_Preprocessing.ipynb`)
   - Loads face images from dataset folder
   - Detects faces using Haar Cascade
   - Applies padding and resizing to 256x256
   - Creates train/test split
   - Saves preprocessed data

2. **Model Training** (`2_Model_Training.ipynb`)
   - CNN architecture with 4 convolutional blocks
   - Batch normalization and dropout
   - Training on student face dataset
   - Evaluation and visualization
   - Saves trained model

### Assignment 3: Transfer Learning
- Uses pre-trained models (VGG16, ResNet50, MobileNetV2)
- Fine-tuning for face recognition
- Compares performance of different architectures
- Generates comparison charts and best model selection

## 🚀 How to Run

### Assignment 1:
```bash
jupyter notebook "Assignment 1/MNIST_Digit_Classification_using_NN_.ipynb"
```

### Assignment 2:

**Step 1: Preprocess Data**
```bash
jupyter notebook "Assignment 2/1_Data_Preprocessing.ipynb"
# Run all cells
```

**Step 2: Train Model**
```bash
## 🚀 How to Run

### Assignment 1:
```bash
jupyter notebook "Assignment 1/MNIST_Digit_Classification_using_NN_.ipynb"
# Run all cells for MNIST digit classification
```

### Assignment 2:
```bash
# Step 1: Preprocess data
jupyter notebook "Assignment 2/1_Data_Preprocessing.ipynb"

# Step 2: Train model
jupyter notebook "Assignment 2/2_Model_Training.ipynb"
```

### Assignment 3:
```bash
jupyter notebook "Assignment 3/Face_Recognition_Transfer_Learning.ipynb"
# Run all cells to train and compare VGG16, ResNet50, MobileNetV2
```ransfer learning comparison
- Best model identification
- Performance visualizations

## 🎓 Key Features

- **Assignment 1**: Neural network basics, MNIST classification
- **Assignment 2**: Face detection, CNN architecture, preprocessing pipeline
- **Assignment 3**: Transfer learning, model comparison (VGG16, ResNet50, MobileNetV2)
- **Visualization**: Training plots, accuracy/loss curves, comparison charts

## 📝 Notes

- All notebooks include detailed explanations and documentation
- Each assignment is self-contained
- Suitable for Google Colab or local Jupyter environment
- Follow the notebooks in order for best understanding

**Assignment 2:**
- Face detection and preprocessing pipeline
- CNN training with accuracy/loss visualization
- Model evaluation on test set

**Assignment 3:**
- Transfer learning with 3 pre-trained models
- Performance comparison charts
- Best model identification