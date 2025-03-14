

#  Leaf Disease Classification  

##  Overview  
This project implements a **deep learning-based classification model** to detect and categorize **leaf diseases** using TensorFlow and Keras. It utilizes **image datasets** for training and evaluation, enabling automatic detection of plant diseases to assist in early intervention.  

##  Dataset  
The dataset consists of **2,273 images** belonging to **10 different classes**, loaded using `image_dataset_from_directory()`.  

##  Technologies Used  
- **TensorFlow & Keras** – Model development  
- **OpenCV & PIL** – Image preprocessing  
- **Matplotlib & Seaborn** – Visualization  
- **Scikit-learn** – Performance metrics  

##  Model Architecture  
- **CNN-based deep learning model**  
- **Input Shape**: (256, 256, 3)  
- **Batch Size**: 32  
- **Training for 30 epochs**  

##  How to Run  
1. **Clone the repository**  
   ```bash
   git clone https://github.com/yourusername/leaf-disease-classification.git
   cd leaf-disease-classification
   ```  
2. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```  
3. **Run the Jupyter Notebook**  
   ```bash
   jupyter notebook LeafDisease.ipynb
   ```  

##  Results  
- The trained model achieves **high accuracy in classifying leaf diseases**.  
- **Confusion matrix and ROC curves** are used to evaluate performance.  

