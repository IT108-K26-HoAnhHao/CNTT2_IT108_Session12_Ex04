# Bài tập 4

## Phần 1. Phân tích: Phân biệt Yêu cầu chức năng và Phi chức năng

*   **Yêu cầu chức năng (Functional Requirements):** Mô tả các tính năng nghiệp vụ cốt lõi mà hệ thống phải thực hiện để phục vụ hoạt động khám chữa bệnh. 
    *   *Ví dụ:* Tiếp nhận bệnh nhân, tạo mới hồ sơ bệnh án điện tử, tra cứu lịch sử khám bệnh, kê đơn thuốc và quản lý kết quả xét nghiệm.
*   **Yêu cầu phi chức năng (Non-Functional Requirements):** Mô tả các tiêu chuẩn chất lượng, khả năng vận hành, hiệu năng và đặc biệt là các tiêu chuẩn bảo mật của hệ thống.
    *   *Ví dụ:* Mã hóa dữ liệu bệnh nhân theo chuẩn y tế, kiểm soát quyền truy cập chặt chẽ (Role-Based Access Control), thời gian phản hồi trang dưới 2 giây và đảm bảo tính sẵn sàng cao của hệ thống.


## Phần 2. Triển khai: Hệ thống Clinic-Cloud tích hợp

*   **1. Tài liệu Word (SRS):** Soạn thảo đặc tả yêu cầu cho module bệnh án điện tử, phân cấp tiêu đề rõ ràng bằng `Heading 1`, `Heading 2` để kích hoạt Navigation Pane và quản lý mục lục tự động.
*   **2. Bảng tính Excel (Quản lý 1000 hồ sơ bệnh nhân):** Thiết lập cấu trúc dữ liệu theo chuẩn Database Mindset (1 hàng Header duy nhất ở đầu, không để hàng trống hoặc chứa hàng tổng cộng ngắt quãng ở giữa các bản ghi) để bộ lọc tự động (`Ctrl + Shift + L`) hoạt động chính xác trên toàn bộ 1000 dòng dữ liệu.
*   **3. Bài thuyết trình PowerPoint:** Trực quan hóa số liệu dịch bệnh bằng biểu đồ hình vành khuyên tối giản (**Donut Chart**), giúp báo cáo ngắn gọn, dễ nhìn và làm nổi bật các tỷ trọng dữ liệu quan trọng.



## Phần 3. Kiểm thử: Khắc phục lỗi gán nhãn Heading Styles nhầm (Phím tắt Ctrl + Shift + N)

Khi soạn thảo tài liệu Word, nếu một đoạn văn bản thông thường bị gán nhầm định dạng Heading (khiến đoạn văn bị đẩy vào mục lục tự động hoặc làm sai lệch cấu trúc tài liệu), hãy thực hiện thao tác sau để đưa đoạn văn về trạng thái định dạng văn bản chuẩn (Normal):

1.  **Bôi đen đoạn văn bản** bị gán nhầm nhãn Heading.
2.  Nhấn tổ hợp phím **`Ctrl + Shift + N`** trên bàn phím.
3.  *Kết quả:* Hệ thống sẽ lập tức đưa đoạn văn bản đó về kiểu định dạng chuẩn ban đầu (`Normal Style`), loại bỏ hoàn toàn thuộc tính tiêu đề và giúp cấu trúc tài liệu trở lại đúng quy chuẩn.

