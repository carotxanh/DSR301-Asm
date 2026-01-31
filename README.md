# 🌦️ Dự án Phân tích & Dự đoán Thời tiết tại TP. Hồ Chí Minh

## 📌 Giới thiệu
Dự án này tập trung vào việc **phân tích dữ liệu thời tiết lịch sử tại TP. Hồ Chí Minh** nhằm tìm ra các xu hướng, mối quan hệ giữa các yếu tố khí tượng và **xây dựng mô hình dự đoán nhiệt độ trung bình** cho ngày tiếp theo.

Dự án được thực hiện dưới dạng **Jupyter Notebook (R kernel)**, kết hợp các kỹ thuật:
- Phân tích dữ liệu khám phá (EDA)
- Trực quan hóa dữ liệu
- Học máy (Machine Learning) với mô hình hồi quy

---

## 👥 Thông tin nhóm
- **Nhóm**: Group 4  
- **Môn học**: DSR30301m 
- **Học kỳ**: SU25  

---

## 🧪 Dữ liệu sử dụng
- Dữ liệu thời tiết lịch sử tại TP.HCM
- Các thuộc tính chính:
  - Nhiệt độ
  - Độ ẩm
  - Lượng mưa
  - Thời gian (ngày / tháng / năm)


---

## 🧪 Dữ liệu sử dụng
- Dữ liệu thời tiết lịch sử tại TP.HCM
- Các thuộc tính chính:
  - Nhiệt độ
  - Độ ẩm
  - Lượng mưa
  - Thời gian (ngày / tháng / năm)

---

## ⚙️ Công nghệ & Thư viện sử dụng

### Ngôn ngữ
- **R (R 4.x)**

### Thư viện chính
```r
tidyverse   # Xử lý và trực quan hóa dữ liệu
lubridate   # Xử lý dữ liệu thời gian
caret       # Xây dựng và đánh giá mô hình ML
corrplot    # Trực quan hóa ma trận tương quan
