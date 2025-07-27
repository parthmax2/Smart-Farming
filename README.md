
# 🌾 Smart Farming: Crop Recommendation System for Popular Indian Crops  

> 🔬 A Machine Learning-based Web Application to Recommend Suitable Crops Based on Environmental Conditions  
> 👨‍🌾 Built by [Saksham Pathak](https://github.com/parthmax2) | IIIT Lucknow | 94.3% Accuracy | Deployed using Flask  

---

## 📌 Overview  

**Smart Farming** is a crop recommendation system that leverages machine learning to assist Indian farmers in selecting the most suitable crop for cultivation based on key environmental parameters. The system uses a **Random Forest Classifier** trained on soil and climatic data to suggest the best crop from a set of **22 popular Indian crops**.

🌱 This project empowers sustainable agriculture, efficient resource utilization, and smarter farming decisions through AI.  

---

## 🧠 Key Features  

- ✅ **ML-Powered Predictions** (94.3% Accuracy)  
- 🧪 Inputs: Nitrogen, Phosphorus, Potassium, Temperature, Humidity, pH, Rainfall  
- 🌾 Outputs: Rice, Maize, Banana, Cotton, Sugarcane, etc.  
- 📊 Model Used: **Random Forest Classifier**  
- 🌐 **Flask-based Web App** with real-time crop suggestions  
- 🎨 Clean and responsive UI (HTML + CSS + JS)  

---

## 🚀 Live Demo  

[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-Click%20Here-brightgreen?style=for-the-badge&logo=google-chrome)](https://huggingface.co/spaces/parthmax/Smart-Farming)  
> 💡 *Also available locally via `app.py`*  

---

## 🖼️ Web App Screenshot  

![Crop Recommendation System Screenshot](static/images/crop_recommendation_preview.png)  
> 🖼 *Responsive user interface built using HTML, CSS, and JavaScript*

---

## 🖥️ Tech Stack  

| Component     | Technology                |
|---------------|---------------------------|
| 👨‍💻 Language      | Python, HTML, CSS, JS       |
| 🔍 ML Model     | Random Forest Classifier |
| ⚙️ Backend      | Flask (Python)           |
| 🖼 Frontend     | HTML + CSS + JavaScript  |
| 📦 Deployment   | Pickle Model Serialization |

---

## 📂 Project Structure  

```

📁 crop-recommendation
├── 📁 static/
│   └── images/
│       └── crop\_recommendation\_preview\.png
├── 📁 templates/
│   └── index.html
├── 📄 app.py
├── 📄 crop/minmaxscaler.pkl, standscaler.pkl
├── 📄 requirements.txt
├── 📄 Dockerfile
└── 📄 README.md

````

---

## 📊 Model Performance  

| Model             | Accuracy | Precision | Recall | F1-Score |
|------------------|----------|-----------|--------|----------|
| 🌟 Random Forest     | 94.3%    | 92.7%     | 91.5%  | 92.1%    |
| Gradient Boosting | 92.1%    | 90.5%     | 89.3%  | 89.9%    |
| XGBoost           | 91.4%    | 88.9%     | 87.5%  | 88.2%    |
| SVM               | 85.7%    | 83.2%     | 81.6%  | 82.4%    |

📌 **Key Factors Influencing Prediction:**
- Rainfall  
- Soil pH  
- Temperature  
- NPK (Nitrogen, Phosphorus, Potassium)  

---

## 📥 How to Run Locally  

### 1️⃣ Clone the Repository  

```bash
git clone https://github.com/parthmax2/crop-recommendation-system.git
cd crop-recommendation-system
````

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Flask App

```bash
python app.py
```

### 4️⃣ Open in Browser

Visit `http://localhost:5000/` to use the web app.

---

## 📈 Future Enhancements

* [ ] 🌤 Real-time Weather API Integration
* [ ] 📡 IoT-based Soil Sensor Integration
* [ ] 🐛 Pest & Disease Prediction Module
* [ ] 🌍 Satellite/GIS data for advanced insights
* [ ] 🌐 Multilingual and Offline Support

---

## ✍️ Author

**Saksham Pathak**
M.Sc. AI & ML, IIIT Lucknow
🔗 [GitHub](https://github.com/parthmax2) | [LinkedIn](https://linkedin.com/in/sakshampathak)

---

## 📄 License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.

---

## 📚 References

* [IEEE Paper 1](https://ieeexplore.ieee.org/document/10575152)
* [Crop Dataset - Kaggle](https://www.kaggle.com/datasets/atharvaingle/crop-recommendation-dataset)
* Full list of academic references is included in the `paper.pdf`.

---

> 🌱 *"Empowering farmers through AI-driven decisions for a greener tomorrow."*

```