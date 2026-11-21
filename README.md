# alzheimer
Dự án phân tích ảnh MRI dọc bằng 3D-CNN theo dõi tiến triển Alzheimer.
# Ứng dụng Học sâu 3D-CNN trong Phân tích Ảnh MRI Dọc

## Giới thiệu
Dự án sử dụng mạng nơ-ron tích chập 3 chiều (3D-CNN) được xây dựng bằng PyTorch để phân tích chuỗi thời gian của hình ảnh y tế (Longitudinal MRI). Mục tiêu là theo dõi tiến triển và phân loại các giai đoạn của bệnh Alzheimer.

## Phương pháp
- **Dữ liệu**: Khai thác tập dữ liệu OASIS-2 Longitudinal (ảnh 3D .img và dữ liệu lâm sàng).
- **Mô hình**: 3D-CNN tối ưu hóa bằng Adam, hàm suy hao Cross-Entropy.
- **Tiền xử lý**: Chuẩn hóa không gian Tensor 3D, trích xuất bản đồ trừ dọc (longitudinal subtraction maps).

## Kết quả
Sau 10 epochs huấn luyện, mô hình đạt độ chính xác **87.50%** trên tập validation, vượt trội so với các mô hình baseline (SVM, Decision Tree).

## Giấy phép
Dự án này được phân phối dưới giấy phép [MIT License](LICENSE).
