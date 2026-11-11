KHO TRÒ CHƠI HỌC TẬP
====================
Cấu trúc thư mục (đặt cả thư mục kho-game vào kho GitHub của site):

kho-game/
  index.html            <- trang kho trò chơi (học sinh vào đây)
  games.js              <- danh sách trò chơi (xuất ra từ trang Quản lý)
  games/
    go-phim/index.html  <- mỗi trò chơi là một thư mục có file index.html
    ten-game-moi/index.html

Địa chỉ trên Netlify: https://<ten-site>.netlify.app/kho-game/
Trang quản lý: bấm nút "⚙️ Quản lý" (mã PIN mặc định 1234, đổi trong phần Cài đặt kho).

Thêm game mới:
 1. Vào Quản lý, kéo thả file .html của game vào ô "Kéo thả".
 2. Bấm Sửa để chọn lớp, môn, biểu tượng, mô tả.
 3. Bấm "Xuất games.js".
 4. Trên GitHub: Upload games.js (thay file cũ) và file game vào games/<ten-game>/index.html, rồi Commit.
Có thể chép cả thư mục kho-game vào máy trong phòng máy và mở index.html để dùng không cần mạng.
