## 🧬 How to Run and Test Our Code

You can access the complete project via **Google Colab** or **GitHub**:

- **Colab Notebook:** [Team_20_mRNA_Project](https://colab.research.google.com/...)  
- **GitHub Repository:** [Team_20_mRNA_Project_Repository](https://github.com/...)

---

### ⚙️ Steps to Run

1. Open the Colab notebook and click **“Run All.”**
2. When prompted in the *“Uploading Given Datasets and Necessary Files from GitHub”* block, upload the following files:

   - `test.csv` *(Given)*  
   - `training_class.csv` *(Given)*  
   - `training.fa` *(Given)*  
   - `CNN_best_threshold.txt` *(From GitHub – Model & Dataset Folder)*  
   - `CNN_final_model.h5` *(From GitHub – Model & Dataset Folder)*  
   - `LSTM_model.h5` *(From GitHub – Model & Dataset Folder)*  

3. The notebook will automatically execute all steps, including:
   - Data cleaning and preprocessing  
   - Feature extraction and engineering  
   - Model training and evaluation  

---

### 🧠 Model Files and Notes

- When the notebook reaches each *“Model Building”* section, follow the instructions provided under that section.  
- If you have not uploaded the pre-trained models earlier, you will be prompted to download them from GitHub and re-upload them when required.  

---

### 📊 Expected Outputs

After running all cells, you will obtain:

- **Model performance metrics** and relevant diagrams under each model implementation block  
- **Combined ROC curves** of all models for comparison  

---

> **Tip:** Ensure that all dataset and model files are uploaded before running the model training blocks to avoid file-not-found errors.
