
## 1. Thiết kế kiến trúc: Mẫu Bug Report Template

Để tránh tình trạng nhắn tin loạn xạ, trôi thông tin khi gặp lỗi vặt về môi trường làm việc (Docker, Port conflict), nhóm bắt buộc phải sử dụng **Bug Report Template** dựa trên 4 mảnh ghép cốt lõi trước khi đặt câu hỏi hỗ trợ:

### [BUG REPORT] - [Tên lỗi ngắn gọn, ví dụ: Port 8080 already in use]
- **1. Context (Bối cảnh):** 
  - Đang thực hiện hành động gì
  - Môi trường: OS gì? Phiên bản Docker/phần mềm liên quan?
- **2. Expected (Kỳ vọng):** 
  - Kết quả đúng ra phải như thế nào
- **3. Actual (Thực tế):** 
  - Triệu chứng lỗi xuất hiện là gì
- **4. Log / Screenshot (Minh chứng):** 
  - Dán đoạn thông báo lỗi (Error log) chi tiết hoặc ảnh chụp màn hình terminal 
```

---

## 2. Sản phẩm hoàn chỉnh: Quy trình 3 bước tra cứu bắt buộc

Trước khi gửi báo cáo lỗi lên nhóm hoặc nhờ trưởng nhóm/đồng nghiệp hỗ trợ, các thành viên bắt buộc phải tự thực hiện tuần tự **3 bước tra cứu** sau để tự giải quyết tối thiểu 80% vấn đề:

1. **Bước 1: Googling (Tìm kiếm chủ động trên Google)**
   - **Cách làm:** Copy nguyên văn đoạn thông báo lỗi hoặc từ khóa chính của lỗi, đặt trong dấu ngoặc kép `""` để tìm kiếm chính xác trên Google.
   - **Mục tiêu:** Kiểm tra xem đã có ai gặp lỗi tương tự và có sẵn hướng giải quyết trên các diễn đàn như StackOverflow, GitHub Issues hay blog công nghệ chưa.

2. **Bước 2: Community Search **
   - **Cách làm:** Sử dụng tính năng Search trực tiếp tại các kho lưu trữ mã nguồn mở hoặc kênh hỏi đáp của nội bộ nhóm/lớp.
   - **Mục tiêu:** Tránh việc tạo ra các câu hỏi/issue bị trùng lặp khi người khác đã hỏi và được giải đáp trước đó.

3. **Bước 3: AI Translation & Analysis **
   - **Cách làm:** Đưa đoạn log lỗi tiếng Anh vào các công cụ AI (như Gemini, ChatGPT) kèm theo câu lệnh: *"Hãy giải thích nguyên nhân gốc rễ của đoạn lỗi log sau và đề xuất các bước khắc phục ngắn gọn, an toàn:"*.
   - **Mục tiêu:** Dịch nghĩa, hiểu rõ bản chất lỗi kỹ thuật và nhận các gợi ý xử lý nhanh chóng, chuẩn xác.
