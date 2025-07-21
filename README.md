# 🚦 Traffic Crash OLAP Analysis
Repository này chứa đồ án cuối kỳ môn Kho Dữ Liệu (OLAP). Dự án xây dựng hệ thống OLAP phân tích dữ liệu tai nạn giao thông tại Chicago, sử dụng SSIS, SSAS, Power BI, Looker Studio và khai phá dữ liệu.

**Dataset**: [Traffic Crashes - Crashes | Kaggle](https://www.kaggle.com/datasets/anoopjohny/traffic-crashes-crashes/data)

---

## Cấu Trúc Dự Án

### Excel Pivot file: 
Bao gồm các bảng tổng hợp (Pivot Table) giúp trực quan hóa số liệu tai nạn giao thông theo các chiều như thời gian, loại tai nạn, địa điểm...

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
  

### SSRS project:
Báo cáo được thiết kế bằng SQL Server Reporting Services (SSRS), thể hiện các biểu đồ và bảng dữ liệu phân tích kết quả tai nạn giao thông:
Số vụ theo tháng/năm
Phân loại nguyên nhân và mức độ nghiêm trọng

### Data mining project:
Áp dụng thuật toán khai phá luật kết hợp (Apriori) để tìm ra các mẫu kết hợp thường xảy ra giữa các yếu tố tai nạn (ví dụ: “Trời mưa” và “Tầm nhìn kém” thường đi kèm với tai nạn nghiêm trọng).

## The information of group.txt
Thành viên và vai trò.

📄 Báo cáo tổng hợp:
Tài liệu tổng hợp quá trình thực hiện, gồm:

Giới thiệu đề tài và dữ liệu

Các công cụ và quy trình thực hiện (ETL, OLAP, Visualization, Mining)

Kết quả và phân tích

Kết luận và đề xuất cải tiến

👉 Được trình bày theo cấu trúc khoa học, phục vụ cho việc trình bày và đánh giá đồ án môn học Kho dữ liệu.

---







