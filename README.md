# Modeling-Visitor-Travel-Patterns-to-Restaurants-in-Urban-Environments

🚀 **Project Overview**  
This research project is an intelligent modeling framework developed to understand and predict visitor traffic patterns to restaurants in urban areas. The project was developed as part of a graduate research initiative at San Diego State University and combines advanced deep learning and econometric modeling to enable data-driven decisions for smart city planning, restaurant operations, and urban mobility systems.

📄 **Read the full project report:**  
[📘 Project Report (Google Docs)](https://docs.google.com/document/d/1CxkWyqrgdAJBMHY8gQ9YILK5AH179-0R/edit?usp=sharing)

💻 **Access the project code:**  
[💾 Source Code (Google Drive)](https://drive.google.com/file/d/1tTHzwM652AZKZVnDmT1nZOPThjLedjaZ/view?usp=sharing)

---

## 📊 Problem Statement

Urban foot traffic to restaurants is shaped by a range of factors including restaurant quality, popularity, distance, and dwell time. This project aimed to:

- Forecast hourly restaurant visitor demand  
- Classify restaurants into popularity tiers  
- Simulate visitor decision-making using interpretable behavior models

---

## 🧠 Methodology

### 🔹 LSTM (Long Short-Term Memory)
- Used for time series forecasting of hourly restaurant demand  
- Achieved **87.82% accuracy**  
- Enables use cases like staffing optimization and delivery planning

### 🔹 Kolmogorov–Arnold Networks (KAN)
- Used for classifying restaurants into Low, Medium, and High popularity tiers  
- Achieved **94.72% classification accuracy**  
- Supports marketing segmentation and performance analysis

### 🔹 Discrete Choice Modeling (DCM)
- Modeled visitor choice behavior using a multinomial logit framework  
- Identified key decision factors:  
  - **Quality** (+0.57), **Dwell Time** (+0.39), **Distance** (–1.20), **Popularity** (–0.31)  
- Offers actionable insights for location strategy and consumer behavior analysis

---

## 🛠️ Tools & Technologies

- **Languages**: Python  
- **Libraries**: TensorFlow, PyTorch, PyKAN, Statsmodels, Scikit-learn, Pandas, NumPy, Matplotlib  
- **Techniques**: LSTM, KAN, Multinomial Logit Model (DCM), SMOTE for class balancing, Feature Engineering, MinMaxScaler and StandardScaler for normalization

---

## 🌍 Real-World Applications

- **Restaurant Operations**: Forecast rush hours, optimize resource allocation  
- **Urban Planning**: Inform zoning and public transit adjustments  
- **Mobility Services**: Enhance delivery routing and surge pricing  
- **Retail Analytics**: Understand traffic patterns to support site selection and strategy

---

## 📈 Key Highlights

- Built an interpretable AI pipeline combining deep learning and behavior modeling  
- Processed and modeled 6K+ mobile location records for analysis  
- Delivered insights on visitor behavior and demand patterns to guide business and city infrastructure decisions
