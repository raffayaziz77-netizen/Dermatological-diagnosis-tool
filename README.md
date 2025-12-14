**Dermatological Diagnosis Tool**

\*\*Dermatological Diagnosis Tool\*\* is a deep learning project designed to automatically identify various dermatological conditions from \*\*skin lesion images\*\*, helping doctors and patients achieve faster and more accessible diagnoses.

\---

**Overview**

This project uses a \*\*ResNet-based Convolutional Neural Network (CNN)\*\* to classify skin diseases from medical images.    
It demonstrates the potential of AI in healthcare diagnostics by assisting in the early detection of dermatological conditions through automated image analysis.

\---

**Tech Stack**

\- \*\*Python 3.x\*\*  
\- \*\*PyTorch\*\* – model building and training    
\- \*\*Torchvision\*\* – transforms and image handling    
\- \*\*Timm\*\* – pre-trained ResNet model    
\- \*\*Pandas / NumPy\*\* – data handling    
\- \*\*Pillow\*\* – image processing    
\- \*\*scikit-learn\*\* – metrics and class balancing    
\- \*\*KaggleHub\*\* – dataset access    
\- \*\*Google Colab\*\* – training environment  

\---

**Project Structure**

Dermatological-Diagnosis-Tool/  
│  
├── model/  
│ └── model.pth \# Trained ResNet model (link included inside)  
│  
├── src/  
│ ├── derma\_test.py \# Model testing / inference  
│ ├── train.py \# (optional) Training script  
│  
│  
├── requirements.txt  
├── .gitignore  
└── README.md

**How to Run**

1\. \*\*Clone the repository\*\*  
   \`\`\`bash  
   git clone https://github.com/raffayaziz77-netizen/Dermatological-diagnosis-tool  
   cd Dermatological-Diagnosis-Tool  
Install dependencies

pip install \-r requirements.txt  
Run the model

python src/derma\_test.py  
✅ Works on both CPU and GPU

**Model Information**

Model Type: Efficentnet-B3  
Framework: PyTorch  
Dataset: Public dermatology dataset  
Input: Skin lesion image  
Output: Predicted disease class  
Trained Model: Stored in /model/model.pth (link inside folder)

**Future Enhancements**

Improve model accuracy using EfficientNet / Vision Transformers  
Add real-time webcam-based skin scan  
Build a web interface for public use (Streamlit / Flask)  
Include disease probability scores and confidence metrics

**Author**  
Muhammad Raffay Aziz  
📧 raffayaziz77@gmail.com

**🪪 License**  
This project is intended for educational and research purposes only.  
It is not a substitute for professional medical advice or diagnosis.

