
# 🧠 CNN-Based Image Classification Project

This project implements a **Convolutional Neural Network (CNN)** using PyTorch to classify images into different categories. It includes data preprocessing, model training, and saving of the trained model. The dataset is expected to be structured into `train` and `test` directories, each containing subfolders for individual classes.

---

## 📁 Project Structure

```
├── try2.ipynb                # Jupyter Notebook with CNN implementation
├── /traintestsplit           # Dataset directory
│   ├── train/
│   │   └── class1/, class2/, ...  # Training data
│   └── test/
│       └── class1/, class2/, ...  # Testing data
```

---

## 🚀 Installation & Setup
1. **Clone the repo** or download the `.ipynb` file:
   ```bash
   git clone https://github.com/ankritRisal/CNN-model-Bird-Species-Detection-.git
   
2. **Install dependencies**:
   ```bash
   pip install torch torchvision matplotlib
   ```

3. **Dataset Format**:
   Place your dataset in the following structure:
   ```
   /traintestsplit
   ├── train
   │   ├── classA
   │   └── classB
   └── test
       ├── classA
       └── classB
   ```

3. **Run the notebook**:
   Open `try2.ipynb` and run all cells sequentially in Jupyter Notebook or VSCode.

---

## 🧠 Model Architecture

```
Conv2D → ReLU → MaxPool → 
Conv2D → ReLU → MaxPool → 
Flatten → Linear → ReLU → Linear → Softmax
```

Designed to work on 150x150 input images with data augmentations during training.

---

## 🛠️ Customization

You can modify:
- Image size
- Number of convolution layers
- Learning rate, batch size
- Data augmentations (rotation, flip, resize)

---

## 📌 Requirements

- Python 3.7+
- PyTorch
- Torchvision
- Numpy
- Matplotlib

---

## ✍️ Author

**Ankrit Risal**  
Final-year Computer Engineering student, IOE, Nepal

---

## 📄 License

This project is licensed under the MIT License.
