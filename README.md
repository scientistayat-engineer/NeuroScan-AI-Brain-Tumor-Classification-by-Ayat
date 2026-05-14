🧠 NeuroScan AI: Brain Tumor Classification

📌 Project Overview
NeuroScan AI is a professional-grade Deep Learning system designed to classify and visualize brain tumors from MRI scans. Utilizing the MobileNetV2 architecture, the project achieves an optimal balance between computational efficiency and diagnostic accuracy.

The standout feature of this system is the integration of Explainable AI (Grad-CAM), which provides heatmaps to visualize the specific regions of the MRI scan that influenced the model's classification decision.

🚀 Key Features
Multi-Class Classification: Accurate detection of Glioma, Meningioma, Pituitary tumors, and Healthy (No Tumor) scans.

High Performance: Achieved a robust 87% validation accuracy during training.

Explainable AI (XAI): Uses Grad-CAM to bridge the gap between AI "black-box" decisions and clinical trust.

Advanced Analytics: Includes 3D PCA topology and Radar charts for deep model auditing.

Real-time Inference: Capable of making high-confidence (86%+) predictions on unseen clinical data.

📊 Model Performance Analytics
The following visualizations represent the rigorous evaluation of the NeuroScan AI model. All assets are stored in the assets/ directory.

1. Training Dynamics & Accuracy
Training Loss & Accuracy Curves	Confusion Matrix
Insight: The smooth convergence of the loss curve indicates effective learning without significant overfitting.

2. Statistical Reliability (ROC Curve)
Metric: High Area Under the Curve (AUC) scores demonstrate the model's superior ability to distinguish between tumor types, specifically in challenging Meningioma cases.

3. 360° Performance Audit (Radar View)
Metric: The Radar chart provides a balanced view of Precision, Recall, and F1-Score across all classes, ensuring the model is reliable for clinical scenarios.

4. Data Topology (3D PCA)
Latent Space: This 3D visualization displays how the model clusters different tumor types in high-dimensional space, proving clear class separability.

🛠️ Tech Stack
Language: Python 3.10+

Deep Learning Framework: TensorFlow / Keras

Computer Vision: OpenCV

Data Science: Scikit-learn, Pandas, NumPy

Visualization: Matplotlib, Plotly (for 3D PCA)

Platform: Google Colab (GPU Accelerated)

🎯 Conclusion
NeuroScan AI is more than just a classification tool; it is a step toward making AI in medical imaging more transparent and trustworthy. This project was developed as a milestone within the AI & Data Science program at SMIT (Saylani Mass IT Training).

Developed by: Ayat

AI & Data Science Student at SMIT
