# 🐱 Mèo học Pinyin

Web học pinyin cho học sinh ôn luyện ở nhà: 23 thanh mẫu, 36 vận mẫu (gồm đủ nhóm i, u, ü), âm tiết chỉnh thể, bảng ghép vần, 4 thanh điệu, ghép vần và luyện nghe. Giọng đọc là bản thu âm người thật, chạy được cả khi không có mạng.

## Cấu trúc

| File | Nội dung |
|---|---|
| `index.html` | Toàn bộ giao diện và code (HTML, CSS, JavaScript) |
| `audio.js` | Âm thanh của ~1.600 âm tiết × 4 thanh (không cần sửa) |

## Đưa lên GitHub Pages

1. Tạo repository mới trên GitHub (chọn **Public**).
2. Bấm **Add file → Upload files**, kéo thả `index.html`, `audio.js`, `README.md`, rồi bấm **Commit changes**.
3. Vào **Settings → Pages**, ở mục *Branch* chọn `main` và thư mục `/ (root)`, bấm **Save**.
4. Đợi 1–2 phút, web sẽ có ở địa chỉ `https://<tên-tài-khoản>.github.io/<tên-repo>/`.

## Chạy trên máy

Tải cả thư mục về rồi bấm đúp `index.html`. Hai file phải nằm cùng một thư mục.

## Nguồn âm thanh

- Giọng đọc chính: bộ [mp3-chinese-pinyin-sound](https://github.com/davinfifield/mp3-chinese-pinyin-sound) (public domain), đã lọc tiếng ù/tiếng xì, chỉnh lại cao độ các thanh chưa chuẩn và cân bằng âm lượng. Một số bản thu gốc đọc thiếu âm i (biao4, diao1, diao2, miao1, piao1, tiao1, tiao3, niao1, niao2, lia3 nghe thành bao, dao, mao…); các âm này được dựng lại từ chính giọng đọc đó ở thanh khác (giữ nguyên âm, chỉnh cao độ theo thanh đúng).
- Âm `o` và `eng`: [audio-cmn / Shtooka](https://github.com/hugolpz/audio-cmn), giọng Chen Wang, giấy phép CC BY-SA.
