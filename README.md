# Road Safety Classification 
Classifying road types from satellite images using CNN with performance optimization through Particle Swarm Optimization (PSO)
Project Overview
This project aims to classify road images into 'safe' and 'unsafe' categories using a Convolutional Neural Network (CNN). To improve performance, Particle Swarm Optimization (PSO) is used to tune key hyperparameters such as learning rate and dropout rate. The model is trained on the RTK dataset, which contains labeled images representing various road conditions.
🧠 Technologies Used
- Python 3.x
- TensorFlow / Keras
- PySwarms
- Scikit-learn
- Matplotlib / Seaborn
📁 Project Structure

Dataset/
├── train/
│   ├── safe/
│   └── unsafe/
├── val/
│   ├── safe/
│   └── unsafe/
└── test/
    ├── safe/
    └── unsafe/

⚙️ How to Run
1. Install required libraries using pip (e.g., tensorflow, pyswarms).
2. Place the dataset in the structure above.
3. Run the cells step-by-step.
4. The model will optimize using PSO, train on the best parameters, and report final accuracy.
5. Evaluate performance using test accuracy, confusion matrix, and training plots.
📊 Final Model Performance
Test Accuracy Achieved: 99.54%
Optimized using PSO with 5 particles over 5 iterations.
📎 Dataset Source
RTK Dataset Dataset
👨‍💻 Author
Student Name: [Mohamed Ahmed Mohamed Refaat]
Faculty of Engineering – New Ismailia National University

