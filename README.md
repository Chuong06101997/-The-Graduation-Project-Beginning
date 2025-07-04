# The Graduation Project : Beginning

## Chủ đề: Dự đoán khả năng rời bỏ dịch vụ (Churn) của khách hàng viễn thông bằng Logistic Regression

Dataset: Kaggle - Telecom Customer Churn Prediction.
link: <https://www.kaggle.com/code/bhartiprasad17/customer-churn-prediction.>

## 1. Mục tiêu dự án

Xác định xem khách hàng có rời bỏ dịch vụ hay không (Churn: Yes/No) dựa vào các đặc điểm như:
Giới tính, loại dịch vụ sử dụng, thời gian gắn bó, mức phí hằng tháng, phương thức thanh toán, v.v.

Hỗ trợ doanh nghiệp:
Ưu tiên chăm sóc nhóm khách có nguy cơ rời bỏ cao
Cải thiện trải nghiệm khách hàng → giảm churn.

## 2. CÁC BƯỚC THỰC HÀNH
### 2.1 Tìm hiểu dữ liệu (EDA):
>Quan sát phân bố của cột Churn (bao nhiêu khách rời bỏ, bao nhiêu ở lại).

>So sánh tỷ lệ churn theo từng yếu tố: hợp đồng, internet, phí tháng, thời gian gắn bó,...

>Vẽ biểu đồ (barplot, histogram) để nhìn rõ xu hướng và mối liên hệ với churn.

### 2.2 Xử lý dữ liệu:
>Xử lý dữ liệu thiếu (missing value)

>kiểm tra các lỗi như sai cấu trúc, sai định dạng, duplicate.

> xoá outliners.

>Mã hóa biến phân loại (categorical).

### 2.3 Xây mô hình Logistic Regression:
>Chia tập train/test

>Huấn luyện mô hình

### 2.4 Đánh giá mô hình:

>Dùng accuracy, confusion matrix, ROC/AUC

>Giải thích kết quả

>Xác định biến nào ảnh hưởng nhiều đến việc rời bỏ
### 2.5 Đưa ra hành động:

>Khách hàng có nguy cơ churn cao thường là những ai ?

>Hướng hành động đề xuất cho doanh nghiệp


