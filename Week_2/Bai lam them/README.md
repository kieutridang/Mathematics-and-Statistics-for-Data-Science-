1. Đọc dữ liệu vào df_A
  Tạo 2 dataframe df_train, df_test từ  df_train
  df_train: 80% ngẫu nhiên được lấy từ df_A
  df_test: 20% còn lại

2. Sử dụng ma trận giả đảo  để dự báo CO2 Emission theo 3 features Enginesize, Cylinders, FuelConsumption theo từng bước  sau:
  - Tạo mảng X, y từ df_train
  - Giải hệ phương trình X.w = y (Tính được w1, w2, w3)