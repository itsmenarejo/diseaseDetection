# diseaseDetection
Computer Vision Project: MS and CSVD Detection

### 🧠 Computer Vision Project: MS and CSVD Detection
A Flask-based web application that detects Multiple Sclerosis (MS) and Cerebral Small Vessel Disease (CSVD) from brain MRI scans using a trained Random Forest model and feature extraction techniques.

Users can upload .nii or .nii.gz MRI files, and the system performs:

  * Skull stripping & resizing
  
  * Feature extraction
  
  * Slice-level prediction with majority voting
  
  * Lesion detection visualization using OpenCV
  
  * Results rendered as labeled and marked-up image previews

⚙️ Features
🧠 Supports brain MRI in NIfTI format (.nii/.nii.gz)

🎯 Predicts MS or CSVD with confidence %

🧰 Applies preprocessing (skull stripping, resizing)

🔬 Uses Random Forest classifier on extracted features

🖼 Visualizes detected lesion areas with bounding boxes

📤 Base64-encoded image response (no file saving needed)

🧹 Auto-deletes uploaded images after processing
