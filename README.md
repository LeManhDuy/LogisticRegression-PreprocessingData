# LogisticRegression-PreprocessingData
Bài tập (Phần 5.1)

Viết chương trình đánh giá độ chính xác của thuật toán hồi quy logistic trong 
bài toán dự báo Sự sống/chết (Survived) của hành khách lên tàu Titanic dựa 
trên Độ tuổi (Age) và Giá vé (Fare) mà họ đã mua trong 14 tổ hợp làm sạch dữ 
liệu sau:

- 7 kỹ thuật xử lý dữ liệu trống (Median/Mean/Mode imputation coi như 3 kỹ 
thuật khác nhau, kỹ thuật tạo đặc trưng mới phải sử dụng đồng thời biến Age 
và biến bổ sung Age_NAN để dự báo)

- 2 trường hợp Không xử lý ngoại lệ & Có xử lý ngoại lệ (đồng thời trên 2 biến 
Age và Fare)
Lập bảng báo cáo độ chính xác của thuật toán trong 14 trường hợp trên và cho 
biết độ chính xác cao nhất và thấp nhất xảy ra trong trường hợp nào. Phân tích 
vì sao độ chính xác cao/thấp như vậy (Train/Test phân theo tỉ lệ 70/30 như 
chương trình mẫu, mỗi trường hợp cần thử nghiệm 10 lần với random_state=0 
đến 9 và lấy trung bình để được độ chính xác trung bình của thuật toán). 
28

Bài tập (Phần 5.2)

- Đề xuất các kỹ thuật chuẩn hoá dữ liệu phù hợp để cải thiện độ chính xác 
của thuật toán hồi quy logistic trong bài toán dự báo Sự sống/chết (Survived) 
của hành khách lên tàu Titanic dựa trên Độ tuổi (Age) và Giá vé (Fare) mà họ 
đã mua. 

- Cho biết độ cải thiện (%) về độ chính xác dự báo khi áp dụng kỹ thuật chuẩn 
hoá dữ liệu đã đề xuất kết hợp với 1 trong 14 tổ hợp kỹ thuật làm sạch dữ 
liệu của Bài tập Phần 5.1
