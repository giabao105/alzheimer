# Hướng dẫn Đóng góp (Contributing Guidelines)

Cảm ơn bạn đã quan tâm và muốn đóng góp cho dự án **Phân tích Ảnh MRI Dọc bằng 3D-CNN**! Chúng tôi hoan nghênh mọi sự hỗ trợ từ cộng đồng, từ việc sửa lỗi (bug fixes), cải thiện tài liệu, đến việc bổ sung tính năng mới cho mô hình.

Để quá trình hợp tác diễn ra suôn sẻ, vui lòng tuân thủ các quy tắc dưới đây.

## 1. Báo cáo lỗi (Report a Bug)
Nếu bạn phát hiện lỗi trong quá trình huấn luyện hoặc tiền xử lý dữ liệu, vui lòng tạo một **Issue** trên GitHub và cung cấp các thông tin sau:
*   Mô tả chi tiết về lỗi (bao gồm thông báo lỗi trên terminal nếu có).
*   Các bước để tái tạo lại lỗi đó.
*   Cấu hình môi trường của bạn (phiên bản Python, PyTorch, OS).

## 2. Quy trình Đóng góp Code (Pull Request)
Nếu bạn muốn trực tiếp sửa lỗi hoặc cải tiến code, hãy làm theo các bước sau:
1.  **Fork** repository này về tài khoản của bạn.
2.  Tạo một nhánh mới (Branch) chứa các thay đổi của bạn: 
    `git checkout -b feature/ten-tinh-nang-moi` hoặc `git checkout -b fix/sua-loi-gi-do`
3.  Tiến hành thay đổi và **Commit** mã nguồn:
    `git commit -m "Thêm tính năng chú ý (Attention) cho mô hình 3D-CNN"`
4.  **Push** nhánh đó lên kho lưu trữ fork của bạn:
    `git push origin feature/ten-tinh-nang-moi`
5.  Mở một **Pull Request (PR)** trên repository gốc. Vui lòng mô tả rõ ràng những thay đổi bạn đã thực hiện trong PR.

## 3. Tiêu chuẩn Mã nguồn (Coding Standards)
*   Code Python phải tuân thủ chuẩn **PEP 8**.
*   Các hàm và lớp (Class) quan trọng trong mô hình 3D-CNN cần có docstring giải thích tham số đầu vào và kết quả trả về.
*   Không đưa các file dữ liệu nặng (như `*.img` hoặc `*.pth` kích thước lớn) vào trong commit.

Cảm ơn bạn đã dành thời gian đóng góp!
