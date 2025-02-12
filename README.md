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

<img src="https://drive.google.com/uc?export=view&id=1BPoUNED8oJBz--3nS0TW67mIppJIvYPl" width="400" alt="CNN Model Architecture">

<img src="https://drive.google.com/uc?export=view&id=1hMLMenSc__l1lsZrru5BVMlo-HSg8Uky" alt="FER2013 Dataset Results">

<img src="https://drive.google.com/uc?export=view&id=1qn5gLSICf-KsLzVsE7hJlTD6mhSTu6id" 
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

<img src="https://drive.google.com/uc?export=view&id=11E3Vn41hRmnXZMT60dz0vUy1TUE3YC4s" alt="Sentiment Analysis Results">

  
<img src="https://drive.google.com/uc?export=view&id=12aDoe6CHZHda56KnTHd-X-iZ0-OtU5Xh" 
alt="Hình ảnh từ Google Drive" >

---

## 🛠 Xây dựng Website
- **Frontend:** ReactJS + Vite, Ant Design
- **Backend:** NestJS
- **Database:** MongoDB
- **AI Model Execution:** Python-Shell (chạy AI model trong backend)

## 🎯 Demo & Screenshots
<img src="https://drive.google.com/uc?export=view&id=1OLvAMrzTSQJMuvfs6lrindL3zpW6LJOV" alt="Web UI">

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
