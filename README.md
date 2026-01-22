# 🧠 Breast Cancer Prediction using Machine Learning

## 📌 Giới thiệu
Dự án này xây dựng các mô hình **Machine Learning** để **dự đoán ung thư vú** dựa trên các đặc trưng sinh học của khối u.  
Bài toán được mô hình hóa dưới dạng **phân lớp nhị phân (Binary Classification)**, nhằm hỗ trợ phát hiện sớm ung thư và nâng cao hiệu quả chẩn đoán.

---

## 🎯 Mục tiêu dự án
- Xây dựng pipeline Machine Learning hoàn chỉnh
- Tiền xử lý và phân tích dữ liệu y sinh
- Huấn luyện và so sánh nhiều mô hình phân lớp
- Đánh giá mô hình bằng các chỉ số phù hợp
- Trình bày kết quả rõ ràng, trực quan

---

## 📊 Dataset
- **Tên dataset**: Breast Cancer Wisconsin Dataset  
- **Số lượng mẫu**: 569  
- **Số lượng đặc trưng**: 30  
- **Nhãn mục tiêu (Target)**:
  - `0` – Malignant (Ác tính)
  - `1` – Benign (Lành tính)

Dataset bao gồm các đặc trưng mô tả hình dạng, kích thước và kết cấu của khối u, được trích xuất từ ảnh sinh thiết.

---

## ⚙️ Quy trình thực hiện
1. **Khám phá dữ liệu (EDA)**
   - Kiểm tra cấu trúc dữ liệu
   - Phân phối nhãn
   - Kiểm tra missing values

2. **Tiền xử lý dữ liệu**
   - Chuẩn hóa dữ liệu (Standardization)
   - Chia tập Train/Test

3. **Xây dựng mô hình**
   - Logistic Regression  
   - K-Nearest Neighbors (KNN)  
   - Support Vector Machine (SVM)  
   - Decision Tree / Random Forest *(nếu có)*

4. **Đánh giá mô hình**
   - Accuracy
   - Precision, Recall, F1-score
   - Confusion Matrix

5. **So sánh và lựa chọn mô hình tốt nhất**

---

## 🧪 Công nghệ & Thư viện sử dụng
- **Ngôn ngữ**: Python 🐍
- **Thư viện**:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

---

## 📈 Kết quả
- Các mô hình đạt độ chính xác cao (> 90%)
- SVM và Logistic Regression cho hiệu suất ổn định
- Confusion Matrix cho thấy khả năng phân biệt tốt giữa hai lớp Benign và Malignant

---

## 📂 Cấu trúc thư mục
```bash
├── Breast Cancer Prediction using Machine Learning.ipynb
├── README.md
