# 🚦 Traffic Crash OLAP Analysis
Repository này chứa đồ án cuối kỳ môn Kho Dữ Liệu (OLAP). Dự án xây dựng hệ thống OLAP phân tích dữ liệu tai nạn giao thông tại Chicago, sử dụng SSIS, SSAS, Power BI, Looker Studio và khai phá dữ liệu.

**Dataset**: [Traffic Crashes - Crashes | Kaggle](https://www.kaggle.com/datasets/anoopjohny/traffic-crashes-crashes/data)

---

## Cấu Trúc Dự Án

### SSIS project:
Gói ETL được xây dựng bằng SQL Server Integration Services (SSIS), thực hiện:
Tải dữ liệu từ nguồn CSV (Kaggle)
Làm sạch và chuyển đổi dữ liệu
Nạp vào hệ quản trị cơ sở dữ liệu (SQL Server)

### SSAS project:
Mô hình OLAP (Star Schema) xây dựng bằng SQL Server Analysis Services (SSAS), bao gồm:
Thiết kế Data Cube
Tạo các Measure và Dimension
Triển khai truy vấn MDX để phân tích dữ liệu

### Excel Pivot file: 
Bao gồm các bảng tổng hợp (Pivot Table) giúp trực quan hóa số liệu tai nạn giao thông theo các chiều hỗ trợ phân tích thống kê nhanh.

### SSRS project:
Báo cáo được thiết kế bằng Power BI và Locker, thể hiện các biểu đồ và bảng dữ liệu phân tích kết quả tai nạn giao thông

### Data mining project:
Khám phá và phân tích dữ liệu với các thuật toán học máy (Logistic Regression, Random Forest, XGBoost, LightGBM), đánh giá độ chính xác dự đoán.

### BaoCao.pdf: 
Tài liệu báo cáo tổng hợp toàn bộ nội dung đồ án, trình bày chi tiết từng giai đoạn thực hiện, bao gồm:
    1. Giới thiệu đề tài và tập dữ liệu sử dụng: Trình bày bối cảnh, mục tiêu và nguồn dữ liệu phân tích.
    2. Thiết kế và xây dựng kho dữ liệu: Mô tả quá trình xác định bảng Dim và Fact, thiết kế mô hình dữ liệu dạng Star Schema.
    3. Tích hợp dữ liệu bằng SSIS: Thực hiện quy trình ETL (Extract – Transform – Load) để trích xuất, xử lý và nạp dữ liệu vào kho dữ liệu.
    4. Phân tích dữ liệu với SSAS: Xây dựng Cube OLAP để tổ chức dữ liệu phân tích đa chiều, thực thi các truy vấn phân tích bằng MDX và giao diện thủ công.
    5. Trực quan hóa dữ liệu với Power BI Locker: Thiết kế báo cáo trực quan, biểu đồ tổng hợp giúp người dùng khai thác thông tin nhanh chóng.
    6. Khai phá dữ liệu bằng các mô hình học máy: Áp dụng các thuật toán như Logistic Regression, Random Forest, LightGBM để xây dựng mô hình dự đoán và đánh giá hiệu quả.
    7. Đánh giá và kết luận: So sánh hiệu suất các mô hình và rút ra kết luận về khả năng ứng dụng vào phân tích dữ liệu thực tế.

### The information of group.txt
Thành viên và vai trò.


---







