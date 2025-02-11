# ☕ AI-Powered Coffee Shop Web Application

Ứng dụng website cho quán cà phê kết hợp trí tuệ nhân tạo (AI) để nhận diện cảm xúc trên ảnh và văn bản. Dự án sử dụng mô hình CNN cho nhận diện khuôn mặt và mô hình phoBERT để phân tích cảm xúc từ đánh giá của khách hàng.

---

## 🚀 Features
### 🎭 Facial Emotion Detection
- **Mô hình:** CNN (7 Layers, Fully Connected Layer, Output Layer)
- **Datasets sử dụng:**
  - FER2013
  - Emodata
  - FER+
- **Kết quả:**

<img src="https://drive.google.com/uc?export=view&id=1BPoUNED8oJBz--3nS0TW67mIppJIvYPl" width="400" alt="CNN Model Architecture">

<img src="https://drive.google.com/uc?export=view&id=1hMLMenSc__l1lsZrru5BVMlo-HSg8Uky" alt="FER2013 Dataset Results">

<img src="https://drive.google.com/uc?export=view&id=17NC1Rcv0lZXkcWS4CUXfu5Y4TSk4JOPB" 
     alt="Hình ảnh từ Google Drive" 
     >
<img src="https://drive.google.com/uc?export=view&id=1DUnjGFwBkRSPv7CNJyVu0RG4eRmR2GMF" 
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
 git clone https://github.com/your-repo-name.git
 cd your-repo-name
```

### 2️⃣ Backend Setup
```bash
 cd backend
 npm install
 npm run start
```

### 3️⃣ Frontend Setup
```bash
 cd frontend
 npm install
 npm run dev
```

---



---

## 📞 Contact
📧 Email: thanhnguyenhoang171official@gmail.com 
