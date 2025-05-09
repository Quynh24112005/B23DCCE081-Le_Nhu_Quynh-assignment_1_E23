Bài tập lớn 1 – Môn Lập trình Python
Sinh viên thực hiện: Lê Như Quỳnh – B23DCCE081

Giới thiệu
Bài tập này nhằm mục tiêu khai thác và phân tích dữ liệu liên quan đến các cầu thủ thi đấu tại giải Ngoại hạng Anh mùa giải 2024–2025. Các bước thực hiện bao gồm: thu thập dữ liệu, phân tích thống kê, phân cụm theo đặc điểm thi đấu và dự đoán giá trị chuyển nhượng.

Toàn bộ báo cáo được biên soạn bằng LaTeX nhằm trình bày khoa học.

Nội dung chính
Chương 1 – Thu thập dữ liệu
Sử dụng Selenium và BeautifulSoup để thu thập dữ liệu từ fbref.com, lọc các cầu thủ có tổng thời gian thi đấu trên 90 phút.

Lưu dữ liệu vào file results.csv.

Chương 2 – Phân tích và trực quan hóa
Phân tích thống kê mô tả: tìm top/bottom 3 cầu thủ theo từng chỉ số, tính trung bình, trung vị, độ lệch chuẩn.

Trực quan hóa dữ liệu bằng biểu đồ histogram.

Lưu kết quả vào results2.csv và top_3.txt.

Chương 3 – Phân cụm cầu thủ
Áp dụng K-Means để phân nhóm cầu thủ dựa trên các chỉ số thống kê.

Dùng PCA để giảm chiều và biểu diễn trực quan các cụm.

Chương 4 – Dự đoán giá trị chuyển nhượng
Lấy dữ liệu ước tính giá trị chuyển nhượng (ETV) từ footballtransfers.com cho các cầu thủ thi đấu trên 900 phút.

Lưu dữ liệu vào players_over_900_filtered.csv.

Xây dựng mô hình hồi quy sử dụng Gradient Boosting Regressor để dự đoán .
