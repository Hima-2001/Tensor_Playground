# 🧠 TensorFlow Playground – Interactive Neural Network Trainer

An interactive web application built using **Streamlit** to experiment with custom neural networks on synthetic datasets. This tool enables users to explore the impact of architecture, activation functions, optimizers, and hyperparameters on classification tasks.

---

## 🚀 Features

- Choose from 3 datasets:
  - `make_blobs` (Multi-class classification)
  - `make_circles` (Binary classification)
  - `make_moons` (Binary classification)

- Custom neural network builder:
  - Add multiple hidden layers
  - Choose neurons and activation functions (`ReLU`, `Sigmoid`, `Tanh`)

- Optimizer selection:
  - Supports `Adam`, `SGD`, `RMSprop`, `Adagrad`

- Dynamic configuration:
  - Adjustable learning rate, batch size, epochs, and train-test split

- Visual Output:
  - Decision boundary plots
  - Loss graph (Training vs Validation)
  - Final accuracy metrics

---

## 🧰 Tech Stack

| Component       | Tool/Library         |
|----------------|----------------------|
| Frontend UI     | Streamlit            |
| ML Framework    | TensorFlow / Keras   |
| Visualization   | Matplotlib, Seaborn  |
| Datasets        | Scikit-learn (synthetic) |

---

## 📦 How to Run

## 1. Clone this repository:
```
git clone https://github.com/your-username/tf-playground-app.git
cd tf-playground-app
```
## 2. Install dependencies:
      pip install -r requirements.txt

## 3. Run the app:
      streamlit run app.py
---
  ##  📊 Example Output
- Decision boundary updated live after training

- Accuracy metrics and training/validation loss graph
---

## 🧠 Learning Outcomes
- Understand the influence of model architecture and hyperparameters

- Visualize how neural networks learn to separate complex data patterns

- Get hands-on with model training, evaluation, and optimization
