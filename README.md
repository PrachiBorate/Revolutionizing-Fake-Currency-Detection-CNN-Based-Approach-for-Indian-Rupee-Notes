# **Revolutionizing Fake Currency Detection: CNN-Based Approach for Indian Rupee Notes** 💰🔍

## **📌 Overview**
This project introduces **EffiVisionNet**, a deep learning model designed to detect counterfeit Indian currency with high accuracy. The model is trained on a dataset containing real and fake notes and is compared against **ResNet50 and ConvNeXt** to validate its superior performance.

## **🎯 Features**

✅ **Fake Currency Detection** using advanced CNN models  
✅ **EffiVisionNet vs. ResNet50 & ConvNeXt** – Performance Comparison  
✅ **Accuracy of 99% achieved with EffiVisionNet**  
✅ **Dataset sourced from real and fake Indian Rupee notes**  
✅ **Graphical Analysis** of accuracy, errors, efficiency, and robustness  

---

## **🚀 How to Run**

### **1️⃣ Install dependencies:**
```sh
pip install -r requirements.txt
```

### **2️⃣ Train the model:**
```sh
python train.py
```

### **3️⃣ Evaluate performance:**
```sh
python evaluate.py
```

### **4️⃣ Predict on new notes:**
```sh
python predict.py --image path_to_image
```

---

## **📊 Model Comparison & Results**
EffiVisionNet is compared against ResNet50 and ConvNeXt based on multiple parameters:

- **Accuracy:** EffiVisionNet achieves the highest accuracy (99%)  
- **Efficiency:** Faster inference time compared to other models  
- **Error Rate:** Lower error rate in fake currency classification  
- **Robustness & Flexibility:** Better adaptability to variations in note conditions  

---

## **🖼️ Output Screenshots**
### **Prediction Results on Sample Notes**

<p align="center">
    <img src="static/images/prediction_real.png" width="45%" alt="Real Note Prediction">
    <img src="static/images/prediction_fake.png" width="45%" alt="Fake Note Prediction">
</p>

---

## **🔧 Technologies Used**

- **Python**  
- **TensorFlow 2.17.0** (Deep Learning)  
- **OpenCV** (Image Processing)  
- **Matplotlib** (Graphical Analysis)  

---

## **📌 Future Enhancements**
- 🚀 Extend to detect multiple denominations of Indian Rupee notes  
- 📊 Improve feature visualization to explain model decisions  
- 🏆 Deploy as a real-time mobile application  

---

## **🌟 Contributions & Feedback**

Feel free to fork, modify, or suggest improvements!  
💬 **Have an idea? Open an issue!**

