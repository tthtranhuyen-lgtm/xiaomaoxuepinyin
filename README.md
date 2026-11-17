# 🐱 Mèo học Pinyin

Web học pinyin cho học sinh ôn luyện ở nhà: 23 thanh mẫu, 36 vận mẫu (gồm đủ nhóm i, u, ü), âm tiết chỉnh thể, bảng ghép vần, 4 thanh điệu, ghép vần và luyện nghe. Giọng đọc là bản thu âm người thật, chạy được cả khi không có mạng.

## Cấu trúc

| File | Nội dung |
|---|---|
| `index.html` | Toàn bộ giao diện và code (HTML, CSS, JavaScript) |
| `audio.js` | Âm thanh của ~400 âm tiết × 4 thanh (không cần sửa) |

## Đưa lên GitHub Pages

1. Tạo repository mới trên GitHub (chọn **Public**).
2. Bấm **Add file → Upload files**, kéo thả `index.html`, `audio.js`, `README.md`, rồi bấm **Commit changes**.
3. Vào **Settings → Pages**, ở mục *Branch* chọn `main` và thư mục `/ (root)`, bấm **Save**.
4. Đợi 1–2 phút, web sẽ có ở địa chỉ `https://<tên-tài-khoản>.github.io/<tên-repo>/`.

## Chạy trên máy

Tải cả thư mục về rồi bấm đúp `index.html`. Hai file phải nằm cùng một thư mục.

## Nguồn âm thanh

- Giọng đọc: bản thu âm `1117` (giọng nữ, mỗi âm tiết đọc đủ 4 thanh), đã cắt riêng từng thanh, bỏ tiếng ồn ở đuôi và cân bằng âm lượng. Tổng cộng 397 âm tiết thu âm × 4 thanh.
- Bản thu không có `xi, qiu, xiu, keng, heng, chua, sei, den`; các âm này được ghép từ chính giọng đọc đó (phụ âm đầu của một âm + phần vần cùng thanh của âm khác, ví dụ xi = "x" của xin + "i" của qi).
- Bản thu cũng không có `lo, nou, nun, rei, reng` (đều là âm hiếm) nên các âm này không có tiếng và tự ẩn khỏi bảng ghép vần.
