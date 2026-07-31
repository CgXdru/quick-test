# 📚 Quick English Quiz (Pro Edition)

Một ứng dụng Web siêu nhẹ (Single-file HTML) giúp tạo và làm bài thi trắc nghiệm Tiếng Anh (như TOEIC) từ dữ liệu thô của file Word. Không cần Database, không cần cài đặt, chạy trực tiếp trên trình duyệt.

🚀 **Trải nghiệm ngay tại đây: https://dainty-panda-2cfe68.netlify.app

---

## ✨ Tính năng nổi bật

*   **Xử lý dữ liệu thô thông minh:** Tự động nhận diện và bóc tách câu hỏi/đáp án từ đoạn text copy dán lộn xộn từ file Word bằng Regex.
*   **Import / Export JSON:** Cho phép nạp đáp án nhanh và lưu toàn bộ Đề thi + Đáp án thành 1 file `.json`. Lần sau học chỉ cần Import là bắt đầu làm bài ngay.
*   **Trải nghiệm thi thực tế:** 
    *   Thanh điều hướng (Sidebar) trực quan, biết ngay câu nào đúng/sai/chưa làm.
    *   Trộn đề (Shuffle) ngẫu nhiên để chống học vẹt.
    *   Báo kết quả đúng/sai ngay lập tức (Xanh/Đỏ) và tự động chuyển câu.
*   **Auto-save (Khôi phục phiên bản):** Tự động lưu bài đang làm dở vào Local Storage. Lỡ F5 hoặc tắt trình duyệt vẫn không bị mất dữ liệu.

---

## 🛠 Công nghệ sử dụng

Ứng dụng được xây dựng tối giản nhất có thể (MVP) để dễ dàng chia sẻ và chạy trên mọi môi trường:
*   **HTML5 & CSS3:** Giao diện chia đôi màn hình (Split-layout) thân thiện trên cả PC và Mobile.
*   **Vanilla JavaScript (ES6+):** Xử lý luồng logic, DOM Manipulation và LocalStorage không phụ thuộc vào bất kỳ thư viện hay framework bên thứ 3 nào.

---

## 📖 Hướng dẫn sử dụng nhanh

### Cách 1: Chơi hệ "Mì ăn liền" (Tạo mới từ Word)
1. Copy text từ file Word đề thi và dán vào ô nhập liệu ở **Bước 1**.
2. Sang **Bước 2**, chọn đáp án đúng cho từng câu ở bảng phía dưới (hoặc dán chuỗi đáp án có sẵn).
3. Bấm **Bắt đầu làm bài**.

### Cách 2: Chơi hệ "Chuyên nghiệp" (Dùng file JSON)
1. Sau khi tạo xong đề ở Bước 2, bấm nút **"Lưu Quiz này thành file (.json)"** tải về máy.
2. Gửi file JSON đó cho bạn bè.
3. Người nhận vào trang Web, chọn **"Mở file Quiz (.json)"** -> Load file -> Chiến luôn!

---
*Developed for learning purposes.*
