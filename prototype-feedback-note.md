# Ghi chép phản hồi phỏng vấn thử nghiệm Prototype

> **Case nghiên cứu:** Case B — AI Notes: Ghi chú học tập cá nhân  
> **Mục tiêu:** Ghi nhận thực tế hành vi, nhận xét và các quyết định tương tác Người – AI của học viên thử nghiệm qua các phiên phỏng vấn do các thành viên trong nhóm trực tiếp dẫn dắt (Facilitate).

---

## 1. Chi tiết phản hồi thử nghiệm theo từng phiên Facilitator

### 👤 Phiên 1: Đỗ Tú Anh (MSHV: `2A202601272`) facilitate — Tester 1 (`2A202601870`)

- **Option A — Người học tự tìm kiếm:** Tester nhập từ khóa, xem các trích dẫn bài giảng nhưng nhận xét việc tự đọc và gõ lại đáp án vẫn tốn thời gian.
- **Option B — Người học & AI cùng tạo:** Tester chọn Option B làm phương án ưu tiên. Bạn ấy thích việc AI tự tạo sẵn bản nháp thẻ bối cảnh 3 dòng kèm link trích dẫn `[Slide 14, phút 18:22]`, giúp tiết kiệm công sức gõ lại mà vẫn tự kiểm tra được nguồn tin.
- **Option C — AI đề xuất & Nhờ người hỗ trợ:** Tester đánh giá cao việc AI tự chỉ ra phần bối cảnh bị thiếu (`Unknown`), nhưng ngần ngại khi sử dụng tính năng gửi câu hỏi nhờ bạn học vì không muốn làm phiền người khác.
- **Nhận xét trực tiếp của Tester 1:** _"AI viết sẵn bản nháp thế này rất tiện, nhưng bắt buộc phải có link xem lại slide bài giảng gốc bên cạnh để mình kiểm tra xem AI viết đúng không."_

---


## 2. Bốn nhóm quyết định tương tác Người – AI (Human–AI Decisions)

### 1. Kỳ vọng ban đầu đối với người dùng (Expectation)
- Trước khi thực hiện, người dẫn phỏng vấn giải thích rõ giới hạn: AI chỉ đóng vai trò hỗ trợ gợi ý từ bộ tài liệu bài học mẫu, học viên cần tự kiểm tra lại nguồn trích dẫn trước khi sử dụng.

### 2. Phân chia vai trò giữa Người và AI (Role & Agency)
- **AI thực hiện:** Tìm kiếm trích dẫn bài giảng, tạo bản nháp thẻ bối cảnh 3 dòng, đánh dấu các phần thông tin chưa chắc chắn.
- **Học viên thực hiện:** Đọc trích dẫn, chỉnh sửa bản nháp, bấm duyệt (`Approve`) hoặc từ chối (`Reject`).
- **Nguyên tắc can thiệp:** AI tuyệt đối không tự động lưu nội dung khi chưa có sự xác nhận của học viên.

### 3. Minh bạch nguồn tin & Mức độ tin cậy (Evidence & Uncertainty)
- Luôn hiển thị nguồn trích dẫn trực tiếp (`Slide 14, phút 18:22`) bên cạnh các câu giải thích của AI.
- Gắn nhãn phân loại minh bạch 3 trạng thái: `Đã tìm thấy (Found)`, `AI suy đoán (Inferred)` và `Chưa rõ (Unknown)`.

### 4. Quyền kiểm soát của người dùng (Control & Recovery)
- Cung cấp đầy đủ các nút chức năng: `Xem lại`, `Chỉnh sửa`, `Bỏ qua`, `Hủy gửi` và `Reset về trạng thái ban đầu`.
- Cho phép học viên tự quay lại làm bài theo cách truyền thống bất kỳ lúc nào nếu AI đưa ra thông tin không chính xác.

---
## 3. Tổng kết quyết định & Định hướng nhóm chốt

- **Điểm chung của cả 3 tester:** Đều coi trọng tính minh bạch của trích dẫn bài giảng gốc và yêu cầu con người bắt buộc phải có bước duyệt (`Approve`) trước khi lưu.
- **Định hướng nhóm chốt (Hybrid Solution):** Tự động tạo bản nháp giải thích kèm link bài giảng gốc (Option B), đồng thời tích hợp ô tìm kiếm trích dẫn nhanh (Option A). Mọi nội dung do AI gợi ý đều bắt buộc qua bước học viên xem và bấm duyệt mới được lưu lại.
