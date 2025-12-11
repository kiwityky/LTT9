# Kỳ Thú – Hồn Việt

Dự án là bản demo trò chơi bàn cờ Kỳ Thú với chủ đề văn hóa Việt Nam. Ứng dụng thuần HTML/CSS/JavaScript, hiển thị bàn cờ 9x7 cùng quân đỏ và xanh lá, kèm các câu hỏi kiến thức Việt Nam khi di chuyển vào ô đặc biệt.

## Cách chạy
- Mở trực tiếp tệp `index.html` trong trình duyệt, hoặc
- Chạy một webserver tĩnh (ví dụ `python -m http.server 8000`) tại thư mục dự án rồi truy cập `http://localhost:8000`.

## Cách chơi nhanh
- Mỗi lượt, nhấp chọn quân để xem nước đi hợp lệ rồi nhấp vào ô sáng để di chuyển.
- Thanh bên phải hiển thị lượt hiện tại, mô tả quân đã chọn, nút **Ván mới** và nhật ký bước đi.
- Khi quân đi vào ô có câu hỏi, trả lời chính xác để mở khóa ô cho các lượt sau.
- Trò chơi kết thúc khi một bên không còn quân hoặc không thể di chuyển.

## Cấu trúc thư mục
- `index.html`: Khung HTML chính và liên kết tới tệp CSS/JS.
- `style.css`: Giao diện bàn cờ, quân cờ và thanh điều khiển.
- `script.js`: Logic trò chơi, luật di chuyển, xử lý câu hỏi và cập nhật giao diện.
- `img/`: Logo ứng dụng.
