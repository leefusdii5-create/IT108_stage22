

### A. Sử dụng Công thức Prompt 3 Thành phần
Để nhờ AI giải thích lỗi này một cách bình dân và dễ hiểu nhất, áp dụng cấu trúc Prompt 3 thành phần (Bối cảnh - Vấn đề - Kỳ vọng):
> *"Tôi đang dùng Terminal trên máy tính để thực hiện lệnh đẩy code lên GitHub (`git push origin main`) nhưng nhận được thông báo lỗi `error: open(".git/FETCH_HEAD"): Permission denied`. Hãy giải thích nguyên nhân gốc rễ của lỗi này bằng ngôn từ bình dân, dễ hiểu nhất đối với một người mới học lập trình và gợi ý các hướng giải quyết an toàn."*

### B. Xử lý khi AI hướng dẫn dùng quyền "Run as Administrator"
- **Thực tế kỹ thuật:** Khi AI hoặc tài liệu hướng dẫn chạy lệnh dưới quyền Quản trị viên (`Run as Administrator` trên Windows hoặc `sudo` trên macOS/Linux), điều này giúp cấp quyền ghi/đọc tạm thời cho thư mục hệ thống.
- **Minh họa & Chú ý chụp ảnh màn hình:**
  - Khoanh vùng vùng thông báo lỗi trong Terminal.
  - Che/bảo mật các thông tin cá nhân nhạy cảm (như tên tài khoản người dùng, token cá nhân, địa chỉ IP hoặc thông tin định danh repo riêng tư).

### C. Soạn tin nhắn nhờ giảng viên hỗ trợ (Bug Reporting Framework)
Nếu sau khi thử các cách mà vẫn không khắc phục được lỗi, gửi tin nhắn nhờ giảng viên theo chuẩn Bug Reporting Framework:

### [YÊU CẦU HỖ TRỢ LỖI GIT] - Lỗi Permission Denied khi git push

- **1. Context (Bối cảnh):** 
  - Đang thực hiện thao tác đẩy code (`git push origin main`) lên kho lưu trữ GitHub cá nhân.
  - Môi trường: Hệ điều hành Windows / Terminal (PowerShell).
- **2. Expected (Kỳ vọng):** 
  - Code được đẩy lên GitHub thành công và đồng bộ mã nguồn kịp deadline.
- **3. Actual (Thực tế):** 
  - Terminal trả về thông báo lỗi: `error: open(".git/FETCH_HEAD"): Permission denied`. Đã thử đóng mở lại terminal và chạy lại nhưng không được.
- **4. Log / Screenshot (Minh chứng):** 
  - Đính kèm ảnh chụp màn hình terminal (đã che thông tin cá nhân) hiển thị đoạn lỗi chi tiết. 
  - Mong thầy/cô hỗ trợ hướng xử lý phần quyền thư mục `.git` này ạ. Em xin cảm ơn!
```

