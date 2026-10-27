# OnboardAI – Hành trình hội nhập nhân sự mới (prototype frontend)

## Vai trò / màn hình New Hire
- `index.html`: Dashboard tổng quan, tiến độ và nhiệm vụ sắp tới.
- `newhire-checklist.html`: Checklist với tìm kiếm, lọc, đánh dấu hoàn thành, tiến độ và localStorage.
- `newhire-ai-help.html`: Policy Q&A mô phỏng bằng bộ câu trả lời JavaScript theo từ khóa; không gọi AI API thật.

## Công nghệ
HTML5, CSS3 (Flexbox/Grid/media queries), JavaScript thuần, localStorage.

## Chạy thử
Mở `index.html` hoặc chạy bằng VS Code Live Server. Dùng cùng một browser/origin để chia sẻ trạng thái checklist qua localStorage.

## Những gì hoạt động trong prototype
- Checklist: search, filter, checkbox, tính tiến độ, lưu trạng thái trong trình duyệt.
- Dashboard: đọc trạng thái checklist và hiển thị nhiệm vụ chưa hoàn thành.
- AI Help: tìm câu trả lời trong dữ liệu mẫu, trạng thái đang xử lý, câu trả lời/nguồn mô phỏng và thông báo khi không đủ dữ liệu.
- Responsive navigation cơ bản.

## Giới hạn cần trình bày trung thực
Đây là prototype frontend dùng dữ liệu mẫu. Chưa có backend, đăng nhập thật, đồng bộ dữ liệu giữa các thiết bị hoặc AI API thật. Các ngày và chính sách hiển thị là dữ liệu demo, cần được nhóm xác nhận trước khi dùng như thông tin thật.

## Liên kết cần cập nhật
- Figma/Canva: bổ sung link đúng của nhóm.
- GitHub: https://github.com/mscpxbmp/OnboardAI-Checklist
- GitHub Pages hiện tại: https://mscpxbmp.github.io/OnboardAI-Checklist/ (sau khi cập nhật, kiểm tra lại từng trang trên Pages).
- Video OBS: bổ sung link sau khi upload.
