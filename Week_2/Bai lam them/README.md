1. Đọc dữ liệu vào df_A
  Tạo 2 dataframe df_train, df_test từ  df_train
  df_train: 80% ngẫu nhiên được lấy từ df_A
  df_test: 20% còn lại

2. Sử dụng ma trận giả đảo để dự báo CO2 Emission theo 3 features Enginesize, Cylinders, FuelConsumption theo từng bước sau:
  - Tạo mảng X, y từ df_train
  - Giải hệ phương trình X.w = y (Tính được w1, w2, w3)

Gợi ý:
  Thêm 1 cột vào df_test tên Prediction1 với w1, w2, w3 đã có.

3. Sử dụng Gradient Descent với 2 features Enginesize, Cylinders, FuelConsumption tính  CO2 Emission
  - Viết  hàm Gradient Descent (alpha, X, y, numIterations) với X = [1, Enginesize, Cylinders, FuelConsumption] => Trả về theta [w0, w1, w2, w3]
  - Dự báo thêm 1 cột Prediction2 trong df_test theo công thức đã tính.

Gởi email cho thầy: dtk@hcmus.edu.vn