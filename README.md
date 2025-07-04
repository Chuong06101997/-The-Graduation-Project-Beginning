# The Graduation Project : Beginning

## Chủ đề: Dự đoán khả năng rời bỏ dịch vụ (Churn) của khách hàng viễn thông bằng Logistic Regression

Dataset: Kaggle - Telecom Customer Churn Prediction.
link: <https://www.kaggle.com/code/bhartiprasad17/customer-churn-prediction.>

## 1. Mục tiêu dự án

>Xác định các yếu tố ảnh hưởng đến việc khách hàng rời bỏ (Churn) trong ngành viễn thông.

>Dự đoán xác suất khách hàng sẽ rời bỏ dịch vụ dựa trên dữ liệu hành vi và hồ sơ cá nhân.

>Hỗ trợ doanh nghiệp đưa ra chiến lược giữ chân khách hàng hiệu quả hơn.

Câu hỏi nghiên cứu:
>Những yếu tố nào làm tăng khả năng khách hàng rời bỏ dịch vụ?

>Mô hình Logistic Regression có thể dự đoán được khách hàng churn với độ chính xác bao nhiêu?

## 2. CÁC BƯỚC THỰC HÀNH
### 2.1 Tìm hiểu dữ liệu (EDA):
> kiểm tra biến Y có cân bằng chưa ?

>Tính tỷ lệ churn tổng thể và theo từng nhóm (giới tính, loại hợp đồng, gói internet…).

>Dùng biểu đồ trực quan (barplot, boxplot, histogram) để phát hiện xu hướng.

>Kiểm tra dữ liệu thiếu, phân bố số liệu, mối tương quan giữa các biến.

### 2.2 Xử lý dữ liệu:
>Loại bỏ dữ liệu thiếu (TotalCharges) hoặc xử lý phù hợp.

>Encode các biến phân loại bằng pd.get_dummies() (One-hot encoding).

>Chuyển Churn từ Yes/No → 1/0.

>Kiểm tra biến nào phù hợp để đưa vào mô hình.

>Tạo biến đầu vào (X), thêm add_constant() nếu dùng statsmodels


### 2.3 Xây mô hình Logistic Regression:
>Chia dữ liệu thành tập huấn luyện và kiểm tra (70/30)

>Dùng statsmodels.Logit() để huấn luyện mô hình

>Xem kết quả summary() để hiểu hệ số và p-value

### 2.4 Đánh giá mô hình:

>Dự đoán xác suất → phân loại 0/1 (dựa vào ngưỡng 0.5)

>Tính accuracy, kiểm tra confusion matrix, ROC/AUC nếu cần

>Kiểm tra mô hình có overfitting không (so sánh train/test)

### 2.5 Đưa ra hành động:

>Phân tích các biến ảnh hưởng mạnh đến churn (dựa vào hệ số và odds ratio)

>Rút ra insight thực tế từ mô hình:

>Hợp đồng ngắn hạn, phí cao, thanh toán điện tử → churn cao

Đề xuất hành động:

>Khuyến khích chuyển sang hợp đồng dài hạn

>Tăng chăm sóc khách hàng có nguy cơ churn cao


