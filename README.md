# Car-price-analysis
Phân tích dữ liệugiá xe hơi người học có thể rút ra những kết luận như sau:
-	Dữ liệu gồm 4 bảng : Catalogue, Sales, Category, Manufacturer
-	Có 89 dòng xe của 29 Hãng xe trong dữ liệu
-	Doanh số bán hàng có sự khác biệt khá lớn giữa dòng xe bán chạy nhất và dòng xe bán ế nhất 
(Wrangler là 45892 và Grand Wagoneer là 4)
-	Xét thấy Chevrolet Traver và Cadillac XT6 có dữ liệu khuyết thiếu ở cột Fuel_efficiency nhưng do dữ liệu về doanh số của 2 dòng xe này vẫn được thu thập nên quyết định không loại bỏ
-	Top 6 hãng xe có doanh số bán hàng cao nhất theo dữ liệu lần lượt là Jeep, Ford, Toyota, MercedesBenz, Audi, Lexus.
-	2 dòng xe bán chạy nhất là Jeep Wrangler và Toyota Highlander và đặc biệt là bỏ khá xa những dòng xe còn lại => Từ đó có thể rút ra rằng có thể lựa chọn làm đại lý phân phối cho 2 hãng xe Jeep hoặc Toyota với mẫu xe chủ lực là Wrangler hoặc Highlander
-	Nhận thấy rằng vào năm 2021 không có dữ liệu doanh số của mẫu xe Jeep Wrangler, tại sao mẫu xe “best seller” của nhà Jeep cũng như Top 1 về doanh số bán hàng năm 2020 – năm đại dịch toàn cầu lại không hề có doanh số trong năm 2021 trong khi những mẫu xe khác vẫn có.
	Có thể dự đoán 2 lý do là dữ liệu không được thu thập hoặc Jeep Wrangler thật sự không có doanh số trong năm 2021.
	Sau khi tìm hiểu thì phát hiện ra được, vào đầu năm 2021 Wrangler đã bị triệu hồi 14410 được sản xuất trong khoảng thời gian từ ngày 24/1 đến 18/3/2021 xe vì lỗi động cơ. Do vậy nên nó đã bị khai tử và không có doanh số trong năm 2021
	Vậy nên cần phải xem xét lại kết luận có thể làm đại lý phân phối cho hãng xe Jeep
-	Từng hãng xe có những tháng bán chạy trong năm khác nhau trong năm, là do từng chiến lược Marketing và chiến lược giảm giá của từng hãng xe. Có thể dựa vào đây để đưa ra những chiến lược cạnh tranh cho đại lý.
-	Lập mô hình hồi quy đa biến, điểm đánh giá gần 100% => Mô hình gần như phù hợp tuyệt đối
