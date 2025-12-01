## 🛍️ Khám Phá Dữ Liệu Bán Hàng Của Doanh Nghiệp Chuyên Nhận Order

[](https://www.python.org/)
[](https://scikit-learn.org/)
[](https://www.google.com/search?q=LICENSE)

Đồ án môn học Phân tích và Trực quan Dữ liệu - DS105 | **TP. Hồ Chí Minh – 12/2023** [cite: 242, 243]

### 💡 Mục tiêu Dự án

Dự án tập trung vào việc **khám phá và dự đoán doanh thu theo ngày** từ bộ dữ liệu đơn đặt hàng của một doanh nghiệp nhỏ chuyên nhận order hàng hiệu. Mục tiêu là hỗ trợ doanh nghiệp xác định nhóm khách hàng tiềm năng và đưa ra chiến lược kinh doanh phù hợp[cite: 473].

### 💻 Công nghệ & Phương pháp

| Loại | Công cụ/Phương pháp | Mô tả |
| :--- | :--- | :--- |
| **Ngôn ngữ** | Python | Xử lý, phân tích, và xây dựng mô hình. |
| **Tiền xử lý** | Chuẩn hóa, Điền khuyết (KNN - The Elbow Method) | Xử lý lỗi nhập liệu, ngoại lai, và giá trị khuyết. |
| **Mô hình hóa** | Regression Models (Random Forest, Ridge, Lasso, GB) | Xây dựng mô hình dự đoán doanh thu theo ngày |
| **Tối ưu** | **GridSearchCV** và **Kiểm chứng chéo 5-folds** | Tinh chỉnh siêu tham số để tìm mô hình tối ưu. |
| **Kết quả** | **$R^{2} > 0.9$** | Mô hình **RandomForest** và **Ridge Regression** cho hiệu suất vượt trội.|

### 📊 Kết quả Chính (Insights)

  * **Hiệu suất:** Các mô hình dự đoán doanh thu đạt kết quả $R^{2}$ trên 0.9, cho thấy khả năng dự đoán cao
  * **Mô hình tốt nhất:** **RandomForestRegressor** và **RidgeRegression** được chứng minh có hiệu suất vượt trội, không bị quá khớp.
  * **Khách hàng tiềm năng:** Phân tích cho thấy khách hàng tiềm năng tập trung order các sản phẩm của **nữ giới**, **màu đen**, **giày** từ trang web **Macys**.


### 👥 Thành viên Thực hiện

  * Nguyễn Thị Mai Trinh (MSSV: 21522718) - **Tiền xử lí + Phân tích thăm dò** 
  * Nguyễn Diệu Phương (MSSV: 21520091) - Phân tích thăm dò + Xây dựng mô hình 
  * Nguyễn Thị Huyền Trang (MSSV: 21520488) - Thu thập dữ liệu + Tiền xử lí + Slide 

-----

Bạn có muốn tôi giúp bạn tạo file **https://www.google.com/search?q=LICENSE** hoặc **.gitignore** cơ bản cho dự án này không?
