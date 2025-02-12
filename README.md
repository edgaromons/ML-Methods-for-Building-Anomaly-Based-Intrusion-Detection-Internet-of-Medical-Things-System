In this project, we:

● Utilized Python and various libraries (Pandas, NumPy, Scikit-learn, Keras, TensorFlow, PyTorch) to develop and evaluate machine learning models (Random Forest, SVM) for anomaly-based intrusion detection. 

● Performed exploratory data analysis (EDA) using visualizations (pie charts) and descriptive statistics to gain insights into Internet of Medical Things (IoMT) telemetry data. 

● Applied data preprocessing techniques, including handling missing values, data normalization (MinMaxScaler), and addressing class imbalance with SMOTE. 

● Evaluated model performance using metrics such as accuracy, F1-score, precision, recall, confusion matrix, and classification report. 

● Demonstrated familiarity with cloud-based environments (Google Colab) for code execution and data storage. 

● Showcased knowledge of deep learning concepts (CNN, LSTM) and hyperparameter optimization (Random Search), although not fully implemented in the current project.


Installing Dependencies from requirements.txt
Follow these steps to install the required Python dependencies on your system.
✅ Prerequisites:
•	Ensure Python (>=3.x) and pip (>=21.x) are installed.
•	Check Python and pip versions:
sh
CopyEdit
python --version
pip --version
📌 Installation Instructions
🖥️ Windows:
1.	Open Command Prompt or PowerShell.
2.	Navigate to the project directory:
sh
CopyEdit
cd path\to\your\project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🍏 macOS & 🐧 Linux:
1.	Open Terminal.
2.	Navigate to the project directory:
sh
CopyEdit
cd /path/to/your/project
3.	Run:
sh
CopyEdit
pip install -r requirements.txt
🔍 Additional Tips:
•	If using a virtual environment, activate it before running the installation:
sh
CopyEdit
# Windows (CMD)
venv\Scripts\activate

# Windows (PowerShell)
venv\Scripts\Activate.ps1

# macOS/Linux
source venv/bin/activate
•	If you face permission issues, try:
sh
CopyEdit
pip install --user -r requirements.txt
•	For system-wide installation, use:
sh
CopyEdit
sudo pip install -r requirements.txt
🛠️ Verifying Installation:
Run:
sh
CopyEdit
pip list
to check if all packages are installed.
