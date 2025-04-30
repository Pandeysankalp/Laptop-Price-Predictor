# 💻 Laptop Price Predictor

Welcome to the **Laptop Price Predictor** – a machine learning web application that estimates the price of a laptop based on its specifications. Whether you're buying, selling, or just exploring, this tool helps you get a realistic market price in seconds.

🌐 **Live App**: [https://laptop-price-predictor-virq.onrender.com](https://laptop-price-predictor-virq.onrender.com)  
📦 **GitHub Repo**: [https://github.com/Pandeysankalp/Laptop-Price-Predictor](https://github.com/Pandeysankalp/Laptop-Price-Predictor)

---

## 🚀 Features

- ✅ Predicts laptop prices using a trained ML regression model
- ✅ Clean, user-friendly web interface
- ✅ Responsive form with dropdowns and sliders
- ✅ Built using Flask, Scikit-learn, and Pandas
- ✅ Trained on real-world laptop data

---

## 📸 Preview

![App Preview](https://user-images.githubusercontent.com/placeholder/image-preview.png)

---

## 🧠 How It Works

1. Users enter details such as:
   - Brand & Type
   - RAM size
   - Weight
   - Touchscreen / IPS display
   - Screen size and resolution
   - CPU, GPU brands
   - HDD & SSD capacity
   - Operating System

2. The app calculates **PPI (Pixels Per Inch)** from screen size and resolution.

3. A trained **regression model** (loaded via Pickle) processes the input and predicts the price.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS (Responsive form UI)
- **Backend**: Python, Flask
- **ML Libraries**: Pandas, NumPy, Scikit-learn
- **Model Storage**: Pickle
- **Hosting**: Render.com

---

## 🔧 Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Pandeysankalp/Laptop-Price-Predictor.git
   cd Laptop-Price-Predictor
