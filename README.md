# TRÒ CHƠI NGHIÊNG ĐẦU – GitHub Pages

Bản này được đóng gói theo kiểu **3 file**, phù hợp upload trực tiếp trên giao diện GitHub.

## File
- `index.html`: chứa toàn bộ giao diện, CSS, JavaScript, ảnh nền và âm thanh tổng hợp.
- `favicon.ico`: biểu tượng trang.
- `README.md`: hướng dẫn.

## Cách đưa lên GitHub Pages
1. Tạo repository mới trên GitHub.
2. Chọn **Add file → Upload files**.
3. Upload cả 3 file vào thư mục gốc repository.
4. Commit.
5. Vào **Settings → Pages**.
6. Chọn **Deploy from a branch**.
7. Branch: `main`, Folder: `/(root)`.
8. Save.
9. Chờ GitHub tạo đường dẫn HTTPS.

## Camera
Camera cần chạy trên HTTPS. GitHub Pages đáp ứng yêu cầu này.
Lần đầu vào trang, trình duyệt sẽ hỏi quyền camera. Hãy chọn **Allow/Cho phép**.

## Nhận diện nghiêng đầu
Website dùng MediaPipe Face Mesh từ CDN. Máy cần Internet ở lần tải trang.
Trước khi chơi, học sinh nhìn thẳng 2 giây để hiệu chỉnh tư thế trung tâm.

## Chỉnh câu hỏi
Trong trang chủ chọn **Bộ câu hỏi**. Có thể:
- Thêm
- Sửa
- Xóa
- Đổi thứ tự
- Xuất JSON
- Nhập JSON

Câu hỏi tùy chỉnh được lưu bằng `localStorage` của trình duyệt.

## Thiết lập
Có thể chỉnh:
- Nhạc nền
- Âm thanh hiệu ứng
- Camera nhỏ
- Độ nhạy nghiêng đầu
- Thời gian giữ đầu
- Đảo hướng trái/phải
- Âm lượng nhạc

## Nhạc
Nhạc nền là nhạc game thiếu nhi được tạo trực tiếp bằng Web Audio API, không dùng bài hát có bản quyền.

## Phím tắt
- `←`: chọn A
- `→`: chọn B
- `F`: toàn màn hình
- `M`: bật/tắt nhạc
- `R`: chơi lại ở màn kết quả
