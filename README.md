# Customer Data Analysis & Segmentation using R 📊

## Project Overview
Dự án tập trung phân tích hành vi mua sắm của khách hàng và dự báo doanh thu cho chuỗi bán lẻ. Sử dụng ngôn ngữ **R** để thực hiện trọn vẹn quy trình từ làm sạch dữ liệu, phân cụm khách hàng (Clustering) đến dự báo chuỗi thời gian (Time Series Forecasting).

## Tech Stack & Libraries
- **Language:** R
- **Data Manipulation:** `tidyverse` (`dplyr`, `tidyr`, `readxl`)
- **Visualization:** `ggplot2` (Custom themes, scales)
- **Machine Learning:** `clustMixType` (K-Prototypes for mixed data), `cluster` (Gower Distance)
- **Forecasting:** `forecast` (ARIMA, ETS), `tseries`

## Key Techniques
### 1. Data Cleaning & Feature Engineering
- Xử lý dữ liệu khuyết thiếu (Missing values) và chuẩn hóa dữ liệu.
- Chuyển đổi dữ liệu hỗn hợp (Mixed Data Types) gồm biến định lượng (Doanh thu) và định tính (Vùng miền, Loại sản phẩm) để chuẩn bị cho mô hình phân cụm.

### 2. Customer Segmentation (Clustering)
- **Challenge:** Dữ liệu chứa cả số và phân loại, không thể dùng K-Means thông thường.
- **Solution:** Áp dụng thuật toán **K-Prototypes** và **Hierarchical Clustering** với khoảng cách **Gower** để phân nhóm khách hàng/chi nhánh.
- **Result:** Xác định được các nhóm khách hàng tiềm năng và đặc điểm chi nhánh (ví dụ: Nhóm tăng trưởng nhanh, Nhóm ổn định).

### 3. Sales Forecasting (Time Series)
- Sử dụng mô hình **ARIMA** và **ETS** để dự báo doanh thu theo tháng.
- Đánh giá độ chính xác của mô hình và vẽ biểu đồ xu hướng (Trend lines).

## Visualizations
(Dự án bao gồm các biểu đồ trực quan hóa doanh thu theo thời gian, biểu đồ phân cụm, và biểu đồ so sánh tăng trưởng giữa các chi nhánh).

## Files Description
- `Analysis_Report.html`: Báo cáo chi tiết dạng R Markdown.
- `Presentation_Slides.pdf`: Slide thuyết trình tóm tắt insight.
- `DataLapDesk.csv`: Dữ liệu mẫu sử dụng trong bài.
