# ☕ AI-Powered Coffee Shop Web Application

Ứng dụng website cho quán cà phê kết hợp trí tuệ nhân tạo (AI) để nhận diện cảm xúc trên ảnh và văn bản. Dự án sử dụng mô hình CNN cho nhận diện khuôn mặt và mô hình phoBERT để phân tích cảm xúc từ đánh giá của khách hàng.

---

## 🚀 Features
### 🎭 Facial Emotion Detection
- **Mô hình:** CNN (7 Layers, Fully Connected Layer, Output Layer)
- **Datasets sử dụng:**
  - FER2013 (35,887 dữ liệu, kích thước 48x48, grayscale, 7 loại cảm xúc (0:Angry, 1:Disgust, 2:Fear, 3:Happy, 4:Sad, 5:Surprise, 6:Neutral)
  - Emodata (78,293 dữ liệu, kích thước 48x48, grayscale, 8 loại cảm xúc (0:Fear, 1:Surprise, 2:Angry, 3:Neutral, 4:Sad, 5:Disgust, 6:Contempt, 7:Happy)
- **Kết quả:**

<img src="https://drive.google.com/uc?export=view&id=1bWwRj0VUUSsA0VHsKKmfk8P3W2FXT1p2" alt="CNN Model Architecture">

<img src="https://drive.google.com/uc?export=view&id=14Im10dS9foLZ48_bFBnzfb7T6GK_N8On" alt="FER2013 Dataset Results">

<img src="https://drive.google.com/uc?export=view&id=1nGZlc5jNEfYFSbGW2UXEgKyyyl78Cs2F" 
     alt="Hình ảnh từ Google Drive" 
     >
### 📝 Sentiment Analysis - phoBERT
- **Mô hình:** phoBERT
- **Dataset:** fbr-vn (VNFoodDrinkReviews.xlsx)
- **Dữ liệu:** 5501 dòng với 3 nhãn cảm xúc: Positive, Negative, Neutral
- 
<img src="https://drive.google.com/uc?export=view&id=1ngHW0LFlV78fB6RkbGdd0FYbRebdaDW3" 
     alt="Hình ảnh từ Google Drive" 
     >
- **Kết quả:**

<img src="https://drive.google.com/uc?export=view&id=1q_-mZeepymgTXLXnLaYLLp4tA-uwaZcn" alt="Sentiment Analysis Results">
---

## 🛠 Xây dựng Website
- **Frontend:** ReactJS + Vite, Ant Design
- **Backend:** NestJS
- **Database:** MongoDB
- **AI Model Execution:** Python-Shell (chạy AI model trong backend)

## 🎯 Demo & Screenshots
<figure style="text-align: center;">
  <img src="https://drive.google.com/uc?export=view&id=1NjvuhWdktflC_iWiu-a4fV25j229kS27" alt="Web UI" style="max-width: 100%; height: auto;">
  <figcaption style="margin-top: 8px; font-size: 0.9rem; color: #555;">Figure 1. Product evaluation function</figcaption>
</figure>

<figure style="text-align: center;">
  <img src="https://drive.google.com/uc?export=view&id=1uBtR2-QhyOuMX2rkWQEKYhQgmlDdpnPy" alt="Web UI" style="max-width: 100%; height: auto;">
  <figcaption style="margin-top: 8px; font-size: 0.9rem; color: #555;">Figure 2. Customer evaluation function of products and services</figcaption>
</figure>

<figure style="text-align: center;">
  <img src="https://drive.google.com/uc?export=view&id=1GUaM0Be970h24RdgBLFOotypKuCVhvKO" alt="Web UI" style="max-width: 100%; height: auto;">
  <figcaption style="margin-top: 8px; font-size: 0.9rem; color: #555;">Figure 3. Results of analysis and identification of customer behavior</figcaption>
</figure>


<figure style="text-align: center;">
  <img src="https://drive.google.com/uc?export=view&id=1HICqA0E8wlUVQbnL-fVq_fdtVk_WuDD_" alt="Web UI" style="max-width: 100%; height: auto;">
  <figcaption style="margin-top: 8px; font-size: 0.9rem; color: #555;">Figure 4. User/customer review management page</figcaption>
</figure>

---

## 📦 Installation & Setup
### 1️⃣ Clone repository
```bash
 git clone https://github.com/thanhnguyenhoang171/emo_website.git
 cd emo_website
```

### 2️⃣ Backend Setup
```bash
 cd be-nestjs
 npm install
 npm run dev
```

### 3️⃣ Frontend Setup
```bash
 cd fe-react
 npm install
 npm run dev
```
### 3️⃣ AI model Setup
```bash
 cd be-nestjs
 python -m venv env
 env\Scripts\activate
 pip install -r requirements.txt
```

---

## 🤖 Model Trained

- emodata datasets link: https://drive.google.com/file/d/1wgGT0OoN6WymQqvM29FQl2BjLj4K1T7n/view?usp=drive_link
- facial emotion detection link: https://drive.google.com/file/d/1S1hJmPCfZY6AKawTbiHiMKpmrVAOAkVG/view?usp=sharing
- sentiment analysis link: https://drive.google.com/file/d/1kFX4cZIZxyjSuILNxZgO3B_bX6zNNtw8/view?usp=sharing


---

## 📞 Contact
📧 Email: thanhnguyenhoang171official@gmail.com 
