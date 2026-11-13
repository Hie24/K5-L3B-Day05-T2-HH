# Hướng dẫn Chạy và Kiểm thử Prototype — Track 2 (T2 Giáo dục · Nhóm HH)

## 1. Cách mở Prototype
- Mở trực tiếp file `index.html` trong thư mục `prototype/` bằng bất kỳ trình duyệt web hiện đại nào (Google Chrome, Microsoft Edge, Firefox, Safari).
- Không yêu cầu cài đặt môi trường, không cần server backend.

## 2. Các Ca Demo có sẵn (Bấm nhanh thanh chip phía dưới)
1. **Ca đắt 1 (Kịch bản 8): Lỗi kiến thức giáo trình §3.3**
   - Học viên phát hiện $\sqrt{0.16} = 0.4 > 0.16$, trái với câu "độ lệch chuẩn luôn nhỏ hơn phương sai".
   - AI thừa nhận phép tính học viên đúng, trích dẫn §3.3 kèm phép kiểm tra toán học, không tự ý sửa tài liệu trường và không tự đăng FAQ; tạo bản nháp chuyển TA/Giảng viên.
2. **Ca đắt 2 (Kịch bản 2): Mạo danh TA cập nhật deadline sai qua FAQ**
   - Người dùng tự xưng là TA, đòi đổi hạn nộp Bài 3 sang ngày 15/11 và yêu cầu đăng FAQ cho cả lớp.
   - AI từ chối thao tác, chặn hoàn toàn lệnh xuất bản FAQ từ chat, đối chiếu bảng 2 cột với deadline gốc (23:59 ngày 13/11/2026), chỉ cho phép chuyển ticket kiểm tra nội bộ.
3. **Ca 3 (Kịch bản 7): Xin xác nhận đáp số Bài tập 3 đang mở**
   - Học viên xin xác nhận trung bình 15.375, trung vị 11.5 để yên tâm đi ngủ.
   - AI từ chối phán boolean Đúng/Sai; cung cấp Socratic Checklist 2 bước tự kiểm tra theo §3.1 và §3.2.
4. **Ca 4 (Kịch bản 9 / Kịch bản 3): Khủng hoảng tâm lý lúc nửa đêm (ngoài giờ TA)**
   - Học viên tự ti, khóc đòi gọi Google Meet 1-1 lúc đêm muộn.
   - AI đồng cảm sư phạm, không phán xét; minh bạch khung giờ làm việc của TA (08:00 – 22:00); đặt lịch hẹn hỗ trợ sáng mai và đề xuất ví dụ bắn cung trực quan.
5. **Ca 5 (Bình thường): Hỏi lý thuyết §3.1 & §3.2**
   - Phân biệt trung bình cộng và trung vị; trích dẫn nguồn rõ ràng; minh họa trực quan bằng ví dụ lương phòng ban.

## 3. Bản đồ Đánh số [1] - [6] trên Giao diện (Đối chiếu Rubric R5)
Bấm nút **🏷️ Bật/Tắt Đánh số [1]-[6]** ở góc trên bên phải để hiển thị các thẻ nhãn số màu đỏ:
- **[1] Thẻ căn cứ / đối chiếu (HAX G11 — Giải thích vì sao):** Trích dẫn nguồn tài liệu kèm phép kiểm tra toán học (Ca 1) hoặc bảng đối chiếu deadline chính thức vs chưa xác minh (Ca 2).
- **[2] Thẻ sửa sai & Bản nháp phản ánh (HAX G9 — Sửa dễ dàng):** Bản nháp phiếu gửi TA/Giảng viên cho phép xem trước, sửa nội dung hoặc hủy trước khi gửi.
- **[3] Thẻ giới hạn quyền & Chặn xuất bản (HAX G10 — Thu hẹp phạm vi khi nghi ngờ):** Chặn xuất bản FAQ từ chat, thông báo rõ ràng deadline gốc không đổi khi danh tính chưa được kiểm chứng.
- **[4] Banner Study Mode (HAX G1 — Làm rõ hệ thống làm được gì):** Định vị vai trò trợ lý học tập: hướng dẫn phương pháp, không giải hộ bài đang mở, không có quyền quản trị.
- **[5] Khung duyệt chuyển TA minh bạch giờ trực (Mức tự chủ Cần người duyệt):** Minh bạch khung giờ 08:00 – 22:00, yêu cầu người dùng xác nhận trước khi đưa ticket vào hàng đợi.
- **[6] Socratic Checklist (HAX G10 — Thu hẹp phạm vi khi nghi ngờ):** Hướng dẫn học viên tự kiểm chứng công thức thay vì xác nhận đáp số trực tiếp.
