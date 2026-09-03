# Thư mục tài liệu dùng chung

Trang web đơn giản, tiếng Việt, hiển thị toàn bộ file PDF/hình ảnh trong một thư mục Google Drive — người xem **không cần có tài khoản Google** hay cài ứng dụng gì.

## Bước 0 — Kiểm tra quyền chia sẻ trên Google Drive (quan trọng nhất)

Nếu bỏ qua bước này, người xem sẽ thấy khung trống hoặc bị yêu cầu đăng nhập.

1. Mở thư mục trên Google Drive.
2. Bấm chuột phải vào thư mục → **Chia sẻ / Share**.
3. Ở mục "Quyền truy cập chung / General access", chọn **"Bất kỳ ai có đường liên kết" (Anyone with the link)**.
4. Vai trò để **"Người xem / Viewer"** là đủ.

## Bước 1 — Đưa trang này lên GitHub (miễn phí, không cần biết lập trình)

1. Vào [github.com](https://github.com) và tạo tài khoản nếu chưa có.
2. Bấm nút **"New"** (hoặc dấu **+** ở góc trên phải) → **"New repository"**.
3. Đặt tên, ví dụ `thu-muc-tai-lieu`, chọn **Public**, rồi bấm **"Create repository"**.
4. Trong trang repo vừa tạo, bấm **"Add file" → "Upload files"**.
5. Kéo thả file `index.html` (trong thư mục này trên máy) vào ô upload, rồi bấm **"Commit changes"**.

## Bước 2 — Bật GitHub Pages để có link công khai

1. Trong repo, vào tab **"Settings"**.
2. Ở menu bên trái, chọn **"Pages"**.
3. Mục "Build and deployment" → **Source: Deploy from a branch**.
4. Chọn nhánh **`main`**, thư mục **`/ (root)`**, rồi bấm **"Save"**.
5. Đợi khoảng 1–2 phút, tải lại trang — link công khai sẽ hiện ở trên cùng, dạng:
   `https://<tên-tài-khoản>.github.io/thu-muc-tai-lieu/`

Gửi link này cho người dùng — họ chỉ cần bấm vào là xem được, không cần biết GitHub hay Google Drive là gì.

## Cập nhật sau này

- **Thêm/bớt file trong Drive**: không cần làm gì thêm, danh sách trên trang tự cập nhật theo Drive.
- **Đổi thư mục Drive khác**: mở `index.html` trên GitHub (bấm biểu tượng bút chì để sửa), tìm và thay `id=1yhSjb4sMRjAx14GLspPT1jRUZLDokXSM` (2 chỗ) bằng ID thư mục mới, rồi **"Commit changes"**.
