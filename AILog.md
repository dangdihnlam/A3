# AI Log – Nhật ký sử dụng AI

**Dự án:** 12 Anh Hùng Amphoreus (fan-made, Honkai: Star Rail)
**Công cụ AI:** Claude (Anthropic)
**Ngày sử dụng:** 21/11/2026

## Tóm tắt

Mình tự thiết kế nội dung và giao diện trang web. AI được dùng để kiểm tra lỗi, gợi ý cách sửa và hướng dẫn đưa dự án lên GitHub. Mình đã đọc, chọn lọc và kiểm tra lại kết quả trước khi dùng.

## Chi tiết các lần sử dụng

| STT | Mục đích | Yêu cầu (prompt) | Kết quả AI trả về | Mình đã làm gì |
|-----|----------|------------------|-------------------|----------------|
| 1 | Kiểm tra lỗi code | Gửi `index.html` và `style.css`, nhờ kiểm tra lỗi | Danh sách lỗi: thẻ HTML sai, thiếu `<head>`, CSS khai báo trùng, thiếu `transition`... | Đọc, hiểu từng lỗi và xác nhận lỗi có thật |
| 2 | Viết lại HTML | Nhờ làm lại `index.html` | File `index.html` có cấu trúc chuẩn, sửa thẻ lỗi, tách phần Liên hệ khỏi footer | Dùng bản mới, kiểm tra lại nội dung và đường dẫn ảnh |
| 3 | Viết lại CSS | Nhờ thêm phần CSS | File `style.css` đã gộp khai báo trùng, thêm hiệu ứng hover, responsive | Dùng bản mới, chạy thử trên trình duyệt |
| 4 | Hướng dẫn GitHub | Hỏi cách tạo repo, bật GitHub Pages, quản lý phiên bản v1/v2 | Các bước dùng Git trong VS Code, tag, nhánh, GitHub Pages | Tự thực hiện lệnh, xử lý các lỗi thực tế (sai thư mục, repo private) |
| 5 | Viết README | Hỏi nên viết gì vào README | Bản mẫu `README.md` | Chỉnh sửa link và thông tin cho đúng với repo của mình |

## Phần do mình tự làm

- Chọn chủ đề, nhân vật, danh hiệu và câu slogan
- Chuẩn bị toàn bộ hình ảnh trong thư mục `images/`
- Thiết kế phong cách màu sắc (nền kem, vàng gold, xanh đêm)
- Tự chạy lệnh Git, tạo repo, bật GitHub Pages

## Đánh giá và lưu ý

- AI giúp tìm lỗi nhanh và gợi ý cách tổ chức code gọn hơn.
- Một số hướng dẫn ban đầu không khớp với tình trạng thực tế của máy (ví dụ tên repo, file nằm sai thư mục), nên mình phải kiểm tra lại bằng `git status`, `git ls-files` rồi mới sửa.
- Mình chịu trách nhiệm về nội dung cuối cùng của sản phẩm.