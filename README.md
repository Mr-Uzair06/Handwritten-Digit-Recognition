# Handwritten Digit Recognition using Neural Networks

📌 Project Overview
This project is a Handwritten Digit Recognition System built using Deep Learning . It uses a Convolutional Neural Network (CNN) to classify handwritten digits from the MNIST dataset . Additionally, a Graphical User Interface (GUI) is implemented using Tkinter to allow users to draw digits and predict them in real time.

---

🚀 Features
✔️CNN Modeltrained on the MNIST dataset for accurate digit recognition.
✔️Interactive GUI for drawing and predicting handwritten digits.
✔️Efficient Preprocessing– Image resizing, grayscale conversion, and normalization.
✔️Model Weightsstored in `Theta1.txt` and `Theta2.txt`.
✔️Easy-to-use Interfacewith a modern UI design.

---

📂 Project Structure

Handwritten-Digit-Recognition/
│── dataset/ # Dataset directory
│ ├── mnist-original.mat# MNIST dataset file
│
│── models/# Model-related files
│ ├── Model.py# Model training and saving
│ ├── theta1.txt# Pre-trained weights (Layer 1)
│ ├── theta2.txt# Pre-trained weights (Layer 2)
│
│── utils/# Utility functions
│ ├── RandInitialize.py # Weight initialization script
│ ├── Prediction.py # Function to predict digits
│
│── gui/# GUI application
│ ├── GUI.py# Tkinter-based user interface
│
│── main.py # Main script to run the program
│── README.md# Project documentation
│── requirements.txt # Required dependencies
│── .gitignore # Git ignore file


---

🛠️ Technologies Used
🔹Python– Core programming language
🔹TensorFlow/Keras– CNN Model training
🔹NumPy– Image processing & array manipulation
🔹Tkinter– GUI for user interaction
🔹PIL (Pillow)– Image manipulation

---

🏗️ Installation Guide

Step 1: Clone the Repository
```bash
git clone https://github.com/Mr-Uzair06/Handwritten-Digit-Recognition.git
cd Handwritten-Digit-Recognition
```
Step 2: Install Dependencies
```bash
pip install -r requirements.txt
```
Step 3: Run the GUI
```bash
python gui/main.py
```

---

🎨 How to Use?
1️⃣ Draw a digitin the canvas area.
2️⃣ Click"Predict"to recognize the digit.
3️⃣ The predicted number will be displayed on the screen.
4️⃣ Click"Clear Canvas"to erase and draw a new digit.

---

📜 License
This project is open-source and available under the MIT License .

---

🤝 Contributing
Want to improve this project? Contributions are always welcome!
1️⃣ Fork this repository.
2️⃣ Create a new branch : `git checkout -b feature-name`
3️⃣ Commit your changes: `git commit -m "Added feature"`
4️⃣ Push to the branch: `git push origin feature-name`
5️⃣ Open a Pull Request🚀

---

📞 Contact
📧Email:uzairsmannur@gmail.com
🔗GitHub:(https://github.com/Mr-Uzair06)

