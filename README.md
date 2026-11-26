# Lịch Để Bàn E-Ink (Âm Lịch & Thời Khóa Biểu)

Trang web hiển thị lịch để bàn phong cách màn hình giấy điện tử (E-Ink) dành cho GitHub Pages.

## Tính năng chính
- **Ngày giờ & Đồng hồ trực tiếp** (hỗ trợ 24h/12h, hiện/ẩn giây).
- **Âm lịch Việt Nam chính xác** (tính theo múi giờ UTC+7, hiển thị Can Chi năm/ngày, ngày lễ, Mùng 1, Rằm).
- **Hoạt cảnh E-Ink** (Tự động theo giờ, Mèo & Tách trà, Cửa sổ mưa, Núi non Thiền, Cây Bonsai).
- **Lịch tháng** (bắt đầu Thứ 2 hoặc Chủ Nhật, bấm vào ngày bất kỳ để xem thời khóa biểu ngày đó).
- **Thời khóa biểu** (tự động đánh dấu tiết/công việc đang diễn ra).
- **Trang Admin & Xem trước trực tiếp (`#admin`)**: Tùy chỉnh bảng màu E-Ink (Cổ điển, 3 màu Đen-Trắng-Đỏ, Giấy ấm, Dark), chỉnh sửa thời khóa biểu, xuất/nhập JSON và tải `index.html` đã nhúng sẵn cấu hình.

## Cách đưa lên GitHub Pages
1. Tạo repository mới trên GitHub (ví dụ: `lich-eink`).
2. Tải lên 2 file `index.html` và `README.md` này vào nhánh `main`.
3. Vào **Settings → Pages → Build and deployment → Branch: `main` / `(root)`** rồi nhấn **Save**.
4. Truy cập:
   - Màn hình hiển thị: `https://<username>.github.io/lich-eink/`
   - Trang Admin cài đặt: `https://<username>.github.io/lich-eink/#admin`
