# 🛍️ Smart Shopping Assistant — FashionMNIST

This project implements a **Smart Shopping Assistant** that utilizes image classification techniques to recognize clothing items from the FashionMNIST dataset. The goal is to simulate a shopping assistant that can identify fashion products and provide intelligent suggestions based on the identified item.

## 📌 Features

* 🔍 **Image Classification** using Convolutional Neural Networks (CNN)
* 👕 Identifies items from the FashionMNIST dataset (e.g., T-shirts, shoes, bags)
* 📊 Displays model training accuracy and loss
* 🧠 Built using **TensorFlow/Keras**
* 🧪 Includes model evaluation on test data
* 💡 Simple UI logic to simulate recommendation behavior based on prediction

## 📂 Project Structure

```
Smart_Shopping_Assistant_FashionMNIST.ipynb  # Main Jupyter notebook
README.md                                    # Project documentation
```

## 🧰 Technologies Used

* Python 3.x
* TensorFlow / Keras
* Matplotlib / NumPy
* FashionMNIST dataset (from Keras datasets)

## 🚀 How to Run

1. Clone the repository or download the `.ipynb` notebook.
2. Open the notebook using [Jupyter Notebook](https://jupyter.org/) or [Google Colab](https://colab.research.google.com/).
3. Run all cells step-by-step to:

   * Load and preprocess the dataset
   * Train the CNN model
   * Evaluate and test predictions
   * Simulate item identification and recommendation

```bash
# Clone this repository
git clone https://github.com/anushka-0907/smart-shopping-assistant.git
cd smart-shopping-assistant
```

4. (Optional) Create a virtual environment and install dependencies.

```bash
pip install tensorflow matplotlib numpy
```

## 📈 Model Performance

The model achieves decent accuracy (\~89–92%) on the test set, which is sufficient for a prototype assistant in fashion item recognition.

## 🎯 Use Case

This assistant can be extended to:

* Detect real product images using transfer learning
* Match items with e-commerce inventory
* Suggest alternative products based on availability or price

## 🧠 Future Work

* Integrate Faster R-CNN for real product detection
* Connect with an e-commerce API for dynamic product suggestions
* Add recommendation logic based on user browsing history
