# DiagnoGen
A GenAI-powered system that predicts diseases from medical images and explains them in human-friendly language using LLMs and RAG.
# 🧠📷 DiagnoGen – Medical Image Explainer using GenAI

DiagnoGen is an intelligent AI-powered system that predicts diseases from medical images and explains them in simple, human-friendly language using Generative AI.

This project simulates a real-world GenAI workflow by combining deep learning with Retrieval-Augmented Generation (RAG) to deliver highly contextual medical insights.

👉 **🔗 [Try the Live Demo on Hugging Face](https://huggingface.co/spaces/Angelin11/xray-genai-diagnosis)**

---

## 🚀 Key Features

- ✅ **CNN-based Prediction**: Uses a trained ResNet50 model to extract features from uploaded medical images.
- ✅ **SVM Classifier**: Efficiently classifies diseases like pneumonia, tuberculosis, etc.
- ✅ **RAG Workflow**: Integrates LangChain to retrieve relevant disease info from custom documents.
- ✅ **OpenAI LLM**: Generates detailed, simplified medical explanations using retrieved context.
- ✅ **Gradio Interface**: User-friendly web UI for uploading images and viewing diagnosis + explanation.

---

## 🧪 Tech Stack

| Tool/Library         | Purpose                                      |
|----------------------|----------------------------------------------|
| **Python**           | Core language for ML and backend logic       |
| **TensorFlow/Keras** | Image feature extraction (ResNet50)          |
| **scikit-learn**     | SVM model for classification                 |
| **LangChain**        | RAG pipeline setup for GenAI reasoning       |
| **OpenAI LLM**       | Disease explanation using natural language   |
| **Gradio**           | Frontend UI for user interaction             |
| **Hugging Face Spaces** | Cloud deployment & hosting               |

---

## 📂 How It Works

1. 🩻 **Upload Image**: A chest X-ray or similar medical image is uploaded via Gradio UI.
2. 🧠 **Predict Disease**: Image is processed by ResNet50 → features are passed to the SVM → predicts the disease class.
3. 📚 **Retrieve Knowledge**: Class label (e.g., "pneumonia") is used as a query to retrieve related documents.
4. 💬 **Explain via LLM**: Retrieved content is passed to OpenAI LLM → generates an understandable explanation.
5. ✅ **Result Displayed**: Final output shows disease prediction + easy-to-understand explanation.

---

## 🧑‍⚕️ Example Use Case

> Upload a chest X-ray image.
>
> 🧠 Prediction: `Pneumonia`  
> 💬 Explanation: "Pneumonia is an infection that inflames the air sacs in one or both lungs. The sacs may fill with fluid..."

---

## 📦 Deployment

Deployed on Hugging Face Spaces  
🔗 **[Live Space URL](https://huggingface.co/spaces/Angelin11/xray-genai-diagnosis)**

---

## 🤖 Project Highlights

- Built to simulate real-world GenAI workflows.
- Designed for healthcare-based academic or personal research projects.
- Modular, clean, and scalable architecture.

---

## 📝 Authors

👩‍💻 **Angelin John**  
📍 Kerala, India  
🎓 BE CSE-AI | Sathyabama Institute of Science and Technology  
🔬 Passionate about GenAI, Deep Learning

---

## 📢 Note

This project is for educational and demonstration purposes only. It should not be used as a substitute for professional medical diagnosis.

---


---

