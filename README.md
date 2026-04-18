# Email_classifier
📌 Project: Email/SMS Spam Detection using Machine Learning
🧰 Requirements

Before running the project, make sure you have:

Python installed (preferably Python 3.7+)
Required libraries:
pandas
scikit-learn
🚀 Step-by-Step Instructions
1. Install Python

If you don’t already have Python:

Download and install it from the official website: https://www.python.org
أثناء installation, make sure to check “Add Python to PATH”
2. Install Required Libraries

Open Command Prompt (Windows) or Terminal (Mac/Linux) and run:

pip install pandas scikit-learn
3. Prepare the Dataset
Download the dataset file named spam.csv
Place it in the same folder where your Python script is saved
4. Create Python Script
Open any code editor (VS Code, PyCharm, Notepad, etc.)
Copy and paste your code into a file
Save the file as:
spam_detector.py
5. Run the Program

In terminal/command prompt:

Navigate to your project folder:

cd path_to_your_folder

Run the script:

python spam_detector.py
6. View Output
The program will display:
Model accuracy (how well it predicts spam)
Prediction result for the sample message

Example output:

Accuracy: 0.98
Spam message
7. Test Your Own Messages

To test custom messages:

Modify this line in the code:
sample = ["Your message here"]
Save and run the program again
🧠 How It Works (Simple Explanation)
Converts text messages into numerical data
Uses a machine learning algorithm (Naive Bayes) to learn patterns
Predicts whether a message is Spam (1) or Not Spam (0)
