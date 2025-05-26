# Malicious URL Detection Using Random Forest
## Project Overview
This project involves building a lightweight and transparent machine learning model from scratch to detect malicious URLs such as phishing, malware, and defacement links. It uses only lexical features and WHOIS-based metadata, making it suitable for real-time, scalable applications like email filters or browser extensions.
##Key Features
• Built a Random Forest Classifier entirely from scratch in Python (no ML libraries).
• Used a dataset of 651,191 URLs spanning four categories: Benign, Phishing, Malware, and Defacement.
• Engineered 12 lexical and metadata-based features including URL length, entropy, symbol counts, and a novel WHOIS-based domain expiration feature to assess domain legitimacy.
• Developed a real-time feature extraction pipeline to support live URL scanning.
• Achieved strong results: 88.21% accuracy, with over 83% precision and recall.
• Future plans include deploying the model as a REST API or browser extension.

##Dataset
The dataset used in this project was sourced from Kaggle and contains over 650,000 labeled URLs.
<a href="https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset">Download the dataset</a>

##Tech Stack
• Python (no external ML libraries)
• WHOIS module
• Manual feature engineering and preprocessing

##Getting Started
1. Clone the repository
2. Download the dataset from Kaggle and place it in the project directory
3. Run the notebook or Python script to train and test the model
