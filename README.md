# CLO4-IDS-ML-Solution: AI-Powered Intrusion Detection System

## 📌 Project Overview
**Course:** Information Security  
**Assignment:** 1 (CLO 4)  
**Developed By:** [Tumhara Naam Yahan Likho]  

## 🎯 Objective & Scenario
In this project, we act as security analysts for "SecureNet Corp." The goal is to augment existing NIDS by developing a Machine Learning Proof-of-Concept (PoC) model. This model classifies network traffic as either **Normal** or **Malicious** using the **NSL-KDD dataset**, simulating a real-world defense against cyber threats like DoS and Probe attacks.

## 🛠️ Tech Stack & Tools
- **Language:** Python
- **Platform:** Google Colab / Jupyter Notebook
- **Libraries:** Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib
- **Algorithm:** Random Forest Classifier

## 📊 Dataset Setup
The project uses the **NSL-KDD Dataset**, a refined version of the KDD'99 intrusion detection benchmark.
- **Source:** [NSL-KDD GitHub Repository](https://github.com/defcom17/NSL_KDD)
- The dataset is loaded directly within the notebook using the raw URL, so no manual download is required to run the code.

## 🚀 How to Run the Code
1. Open the file `Assignment_1_IDS.ipynb` in this repository.
2. Click on the "Open in Colab" button (if available) or download the file to run locally.
3. Run all cells sequentially. The code will:
   - Load the dataset automatically.
   - Preprocess data (Encoding & Scaling).
   - Train the Random Forest model.
   - Display evaluation metrics and graphs.

## 📈 Results Summary
The model was evaluated on unseen test data with the following outcomes:
- **Accuracy:** High accuracy achieved (approx 99%), proving the viability of ML for intrusion detection.
- **Recall:** The model shows a strong ability to detect attacks (True Positives), which is critical for security.
- **Confusion Matrix:** Visualized in the notebook, showing minimal false negatives.

---
*This project serves as a submission for CLO 4: Create solutions to real-life scenarios using different security-related tools.*
