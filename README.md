## 📱 Mobile Price Range Predictor

A **Machine Learning web application** built using **Streamlit** that predicts the **price range of mobile phones** based on their hardware and feature specifications.
The app uses a trained ML model (`best_ml.pkl`) to classify devices into **four price categories**:

| Class | Description       |
| ----- | ----------------- |
| 0     | Low Cost 💸       |
| 1     | Medium Cost 💰    |
| 2     | High Cost 💎      |
| 3     | Very High Cost 🚀 |

---

## 🚀 Features

* User-friendly web interface built with **Streamlit**
* Predicts price range from real-world mobile features like:

  * Battery capacity
  * RAM & Internal Storage
  * Camera specs
  * Display size & resolution
  * Connectivity (3G/4G/5G, Wi-Fi, Bluetooth)
* Instant prediction using a trained ML model

---

## 📂 Project Structure

```
│── app.py               # Streamlit Web App
│── best_ml.pkl          # Trained Machine Learning Model
│── README.md            # Documentation
```

---

## 🏗 Tech Stack

| Technology   | Purpose              |
| ------------ | -------------------- |
| Python       | Backend + Model      |
| Streamlit    | Web UI               |
| NumPy        | Numerical processing |
| Pickle       | Model loading/saving |
| ML Algorithm | Classification model |

---

## 🧠 Model Input Features

The prediction is based on the following mobile specifications:

* Battery Power
* Bluetooth
* Clock Speed
* Dual SIM
* Front Camera & Primary Camera
* 3G / 4G / Wi-Fi / Touchscreen support
* RAM & Internal Memory
* Screen Height & Width
* Pixel Dimensions
* Talk Time
* Mobile Depth & Weight
* Number of Cores

---

## ▶️ Run the Project Locally

### **1️⃣ Clone the repository**

```bash
git clone https://github.com/parshva106/mobile-price-range-predictor.git
cd mobile-price-range-predictor
```

### **2️⃣ Install dependencies**

```bash
pip install streamlit numpy pickle-mixin
```

### **3️⃣ Run the Streamlit app**

```bash
streamlit run app.py
```

---

## 🖥 Application UI Preview

Minimal and clean input interface with a single-click prediction button.

---

## 📁 Code Reference

The full implementation of the Streamlit web app, including input fields and prediction logic, is located in:
**`app.py`** 

---

## 🙌 Contributions

Contributions, issues, and feature requests are welcome!
Feel free to **Fork** and **Star ⭐** the project.

---

## 📬 Contact

**Developer:** Parshva Mehta
📧 Email: *[mehtaparshva106@gmail.com]*

---

