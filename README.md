
🌿 Weed Detection Using Machine Learning

A deep learning–powered system for automatic weed identification in agricultural fields.

⸻

🚀 Overview

This project presents a Weed Detection System using deep learning techniques.
Due to the large dataset size, all images are stored on Google Drive and loaded directly inside the notebook.

The notebook Weed_Detection_v2.ipynb includes:
	•	Dataset loading from Google Drive
	•	Image preprocessing and augmentation
	•	Autoencoder-based feature extraction
	•	CNN model training and validation
	•	Model evaluation and predictions

⸻

👥 Team Members

This project was developed collaboratively by:
	•	Amit Patel
	•	Om Bhati
	•	Harshit Kumar (Data preprocessing + Autoencoder architecture design)

My Contribution:
Worked on data preprocessing, dataset cleaning, and building the Autoencoder-based ML architecture used for feature extraction and improving classification performance.

⸻

📂 Dataset (Google Drive)

The dataset is large and stored externally.

👉 Dataset Link: Add your Google Drive link here

Accessing Dataset in Colab

from google.colab import drive
drive.mount('/content/drive')

Then set your dataset path:

data_path :
  Image dire:"/content/drive/My Drive/images"
  Annotation dir:"/content/drive/My Drive/annotations"
  Mask dir:"/content/drive/My Drive/masks"


⸻

✨ Features
	•	✔️ Google Drive integration for dataset loading
	•	✔️ Robust data preprocessing & augmentation
	•	✔️ Autoencoder-based feature extraction
	•	✔️ CNN architecture for weed classification
	•	✔️ High training & validation accuracy
	•	✔️ Easy-to-run Jupyter Notebook

⸻

## 📁 Project Structure
```
├── Weed_Detection_v2.ipynb     # Model training, evaluation, predictions
├── README.md                   # Documentation
└── (Dataset stored on Google Drive)

⸻
```

🧠 Model Workflow
	1.	Load dataset from Google Drive
	2.	Preprocess images (resize, normalize, augment)
	3.	Extract features using Autoencoder architecture
	4.	Train CNN classifier
	5.	Validate and evaluate model
	6.	Predict on unseen images

⸻

📊 Results

Metric	Value
Training Accuracy	0.9235
Validation Accuracy	0.9364

📌 Validation accuracy being higher indicates good generalization and low overfitting.

⸻

🛠️ Requirements

numpy  
pandas  
matplotlib  
opencv-python  
scikit-learn  
tensorflow  
google-colab  

Install dependencies:

pip install -r requirements.txt


⸻

▶️ How to Run the Project

Using Google Colab (Recommended)
	1.	Clone the repository:

git clone https://github.com/<your-username>/<repo-name>.git

	2.	Open Weed_Detection_v2.ipynb in Google Colab
	3.	Mount Google Drive:

from google.colab import drive
drive.mount('/content/drive')

	4.	Update dataset path
	5.	Run all cells to train or test the model

⸻

📌 Future Enhancements
	•	Improve accuracy using EfficientNet / ResNet
	•	Build real-time weed detection for videos
	•	Deploy model as a web or mobile app
	•	Integrate drone-based weed scanning

⸻

🤝 Contributing

Contributions and suggestions are welcome!
Feel free to open an issue or submit a pull request.

⸻

📜 License

This project is licensed under the MIT License (or specify whichever license you choose).

⸻

👤 Contributors
	•	Amit Patel
	•	Om Bhati
	•	Harshit Kumar (Data preprocessing + Autoencoder design)
