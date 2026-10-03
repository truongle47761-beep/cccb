# Xác minh chấm công

## Cấu trúc
- `index.html` — ứng dụng web chính.

## Đưa lên GitHub Pages
1. Giải nén ZIP.
2. Tạo repository GitHub mới.
3. Upload `index.html` và `README.md` vào thư mục gốc của repository.
4. Vào **Settings → Pages**.
5. Chọn **Deploy from a branch**.
6. Chọn branch `main` và thư mục `/ (root)`.
7. Bấm **Save**.

## Lưu ý Firebase
Bản hiện tại đã chuẩn bị phần giao diện/kết nối Firebase nhưng Firebase Web Config vẫn cần được điền bằng cấu hình của project Firebase của bạn trước khi các chức năng tài khoản và đồng bộ cloud hoạt động.

Không đưa Firebase Admin SDK/private key vào GitHub.
