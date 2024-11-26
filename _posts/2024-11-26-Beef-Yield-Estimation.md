---
layout: post
title: "Introducing Our Beef Yield Estimation Browser Extension"
image: assets/images/beef-yield-extension.jpg
categories: [Machine Learning, Real-Time Analysis]
featured: true
---

Our new **Beef Yield Estimation Browser Extension** uses AI to analyze beef meat quality directly from live video streams or images viewed in your browser. The extension categorizes the meat into three quality levels: **Red** (Poor), **Amber/Yellow** (Medium), and **Green** (Premium), providing real-time analysis to help users assess the readiness of beef for maximum yield.

---

### **Key Project Tasks**

#### **1. ONNX Runtime Web Integration**
To enable **AI inference capabilities** within the browser, we integrated **ONNX Runtime Web**. This allows the extension to process images and video streams in real-time, providing instant feedback on beef meat quality.

#### **2. Loading the AI Model**
A pre-trained AI model is used to classify beef yield into three quality categories. The model processes images and video frames to output one of the three categories: **Red**, **Amber**, or **Green**.

#### **3. Frame Extraction from Live Video Streams**
We developed two methods for **frame extraction**:
- **URL-Specific Extraction**: Focuses on specific websites where beef evaluation is relevant, extracting frames from HTML tags.
- **Universal Extraction**: Works across various websites, capturing frames from the entire browser tab for general use.

#### **4. Inferencing and Displaying Results**
Once frames are captured, the AI model analyzes them, and the results (red, amber/yellow, green) are displayed on the webpage. Users can instantly assess the quality of beef meat directly within their browser.

#### **5. Optional Automated Bidding**
We are exploring the potential for **automating beef bidding** based on quality estimation. This feature is under further research to assess its practicality and value.

---

### **Case Study: User-Driven Corrections and Model Updates**

#### **Problem:**
Occasionally, the AI model misclassifies meat yield quality, affecting the accuracy of recommendations.

#### **Solution:**
To address this, users can manually correct misclassified results, which are then submitted to the server for **model retraining**. This feedback loop helps to improve the model’s accuracy over time, ensuring continuous learning and better predictions.

#### **Benchmark Results:**
Since the introduction of user-driven corrections, the **accuracy of yield classification** has significantly improved, showcasing the power of continuous learning and user input.

---

### **Research and Considerations**

- **Frame Extraction Techniques**: We are evaluating both **URL-specific** and **universal** methods to determine the best solution for extracting frames from live video streams or images.
- **Automated Bidding Feasibility**: We are investigating the potential benefits of automating the bidding process based on beef quality estimation.

---

### **Next Steps**

- **Frame Extraction**: Further research is required to refine the frame extraction process and evaluate the best approach.
- **Automated Bidding**: Begin exploring the feasibility of automating the bidding process based on quality estimation.
- **Development**: Continue the development of the browser extension, starting with **ONNX Runtime Web** integration and model loading.

---

Watch the demo in action on our [YouTube video](https://youtube.com/shorts/Y3dbkEDK-Zs?feature=share) to see the extension in action!
