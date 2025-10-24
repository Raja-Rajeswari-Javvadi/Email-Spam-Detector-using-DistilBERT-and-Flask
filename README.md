# 📧 Email Spam / Non-Spam Detector

This project detects whether an email or SMS message is **Spam** or **Not Spam** using a **fine-tuned DistilBERT model** from Hugging Face.  
It also includes a simple and attractive **Flask web interface** for real-time testing.

---

## 🚀 Features

- Fine-tuned **DistilBERT** model on the **SMS Spam Collection dataset**
- Clean and interactive **Flask UI** for predictions
- Uses **Hugging Face Transformers** for text classification
- Real-time spam probability output with confidence scores
- Deployed via **Ngrok** or any web server

---

## 🧠 Model Details

- **Base Model:** `distilbert-base-uncased`
- **Dataset:** SMS Spam Collection (5,574 labeled messages)
- **Labels:**  
  - `LABEL_0` → Ham (Not Spam)  
  - `LABEL_1` → Spam

---

