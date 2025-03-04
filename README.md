
# **Forensic Reconstruction Using Blood Pattern Analysis**  

## **Overview**  
**Bloodstain Pattern Analysis (BPA)** is an **AI-powered forensic tool** that classifies bloodstain patterns from images. It assists crime scene investigations by identifying the **type of stain**, the **weapon used**, the **impact surface**, and **movement patterns**. The system utilizes a **deep learning model** trained with Keras to analyze uploaded images and provide detailed forensic insights.  

In the future, this project will be extended into a **Flutter-based mobile application**, enabling real-time bloodstain analysis directly from a smartphone camera.  

## **Screenshots**   
![418231929-19c05b67-55ca-443e-ad40-9c736dcd75db](https://github.com/user-attachments/assets/90f40a49-4723-463e-9e9a-c6b731e51bbc)

![418232336-c612ec99-8387-4d91-9b54-506cc373ec68](https://github.com/user-attachments/assets/5a38a97f-17d8-4ee4-ba00-96ff3facaefd)


## **Features**  
- **AI-driven bloodstain classification**  
- **Prediction of forensic attributes**, including:  
  - **Bloodstain Type** (Drop, Flow, Pool, etc.)  
  - **Weapon Used** (Sharp object, blunt force, gunshot)  
  - **Impact Surface** (Ground, wall, torso, head)  
  - **Movement Analysis** (Stationary or moved after impact)  
- **User-friendly web interface** with a modern dark theme  
- **Future Flutter integration** for mobile-based image capture  

## **Model Training**  
The model used in this project is a **Keras-based Convolutional Neural Network (CNN)** trained to classify bloodstain patterns.  

### **Training Process**  
- **Dataset**: The model was trained on a dataset of labeled bloodstain images, categorized into different types based on forensic studies.  
- **Architecture**: The model follows a CNN-based deep learning architecture with multiple **convolutional layers, batch normalization, and dropout layers** for better generalization.  
- **Preprocessing**:  
  - Images are resized to **224×224 pixels**  
  - Normalized pixel values (**0–1 range**)  
  - Data augmentation applied to improve robustness  
- **Loss Function**: Categorical Crossentropy  
- **Optimizer**: Adam  
- **Training Framework**: TensorFlow/Keras  
- **Model Output**: A probability distribution over multiple bloodstain categories  

### **Bloodstain Classes**  
The model classifies bloodstains into the following categories:  
- **Drop**  
- **Flow**  
- **Swipe**  
- **Pool**  
- **Pattern**  
- **HighSpatter**  
- **LowSpatter**  
- **MediumSpatter**  

## **Technology Stack**  
- **Backend:** Flask (Python)  
- **Machine Learning:** TensorFlow, OpenCV, NumPy  
- **Frontend (Current):** HTML, CSS  
- **Frontend (Future):** Flutter for mobile app integration  



## **Installation & Setup**  

### **1. Clone the Repository**  
```sh
git clone https://github.com/your-username/Forensic-Reconstruction-Using-Blood-Pattern-Analysis.git  
cd Forensic-Reconstruction-Using-Blood-Pattern-Analysis
```

### **2. Create a Virtual Environment (Recommended)**  
```sh
python -m venv venv  
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### **3. Install Dependencies**  
```sh
pip install -r requirements.txt  
```

### **4. Run the Application**  
```sh
python app.py  
```
The web application can be accessed at **`http://127.0.0.1:5000/`**  

## **Usage**  
1. Open the web application  
2. Upload an image of a **bloodstain**  
3. Click **"Predict"** to analyze the stain  
4. View the classification results, including:  
   - **Bloodstain type classification**  
   - **Possible weapon used**  
   - **Impact surface analysis**  
   - **Movement patterns**
     


## **Future Enhancements**  
- **Mobile Integration:** The system will be extended into a **Flutter-based mobile app** for real-time image capture and analysis.  
- **Model Optimization:** Improve classification accuracy using larger datasets and advanced deep learning techniques.  
- **Cloud Deployment:** Deploy the service on AWS, GCP, or similar platforms for scalability.  
- **Real-time Processing:** Enhance inference speed for faster analysis.  

## **Contributors**  
This project was developed by:  
- [Hemesh K](https://github.com/Hemeshk2004)  
- [Jacob Gunaseelan J](https://github.com/JacobGunaseelan)  
- [Bharath R](https://github.com/bharathramachandran04)  
- [Divit P](https://github.com/Divit9954)  
