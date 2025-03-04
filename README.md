
# **Forensic Reconstruction Using Blood Pattern Analysis**  

## **Overview**  
This project is a **Flask-based web application** designed to assist forensic investigations by analyzing **bloodstain patterns**. The system utilizes a **deep learning model** to classify bloodstains, providing insights into the **type of bloodstain**, the **possible weapon used**, the **impact location**, and whether there was **movement after the impact**.  

In the future, this system will be extended into a **Flutter-based mobile application**, enabling real-time bloodstain analysis directly from a smartphone camera.  

## **Features**  
- **Bloodstain classification** using deep learning  
- **Prediction of forensic attributes**, including:  
  - **Bloodstain Type** (Drop, Flow, Pool, etc.)  
  - **Weapon Used** (Sharp object, blunt force, gunshot)  
  - **Impact Location** (Ground, wall, torso, head)  
  - **Movement Analysis** (Stationary or moved after impact)  
- **User-friendly web interface** with a dark theme  
- **Future Flutter integration** for mobile-based image capture  

## **Technology Stack**  
- **Backend:** Flask (Python)  
- **Machine Learning:** TensorFlow, OpenCV, NumPy  
- **Frontend (Current):** HTML, CSS  
- **Frontend (Future):** Flutter for mobile app integration  


```

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
   - **Impact location analysis**  
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

---

