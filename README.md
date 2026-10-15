# bye-bye-tranggt 🌸

Thiệp chia tay chị **Giáp Thu Trang**, dựa trên [bye-bye-tamnc](https://github.com/trungph-coder/bye-bye-tamnc) (template gốc [anhnt-24/bye-bye-namtlv](https://github.com/anhnt-24/bye-bye-namtlv)): phong bì, lá thư giấy kẻ, tông hồng.

## Thả ảnh vào `images/`

| Vị trí | Tên file |
|---|---|
| 4 khung lớn ở 4 góc màn hình (màn ≥1024px) | `khung-1.jpg` … `khung-4.jpg` |
| 2 khung hai bên phong bì (màn ≥1024px) | `khung-5.jpg`, `khung-6.jpg` |
| Khung giữa mép trên + ảnh dán trong thư | `chi-trang.jpg` |

Khung nào chưa có ảnh sẽ hiện 📷 kèm tên file cần thả. Dùng đuôi khác (`.png`, `.jpeg`) thì sửa `src` trong `index.html`.

## Sửa chữ
- Nội dung thư: tìm `✏️ Sửa nội dung thư` trong `index.html`.
- Chú thích ảnh: các thẻ `<figcaption>`.
- Nhạc nền: thay `music.mp3`.
- Màu: các biến `--sun-*` trong `:root` đầu file.

## Hiệu ứng
Tia sáng xoay + quầng sáng thở, đom đóm bay lên, hoa rơi, phong bì bồng bềnh có vệt sáng quét + con dấu toả vòng sáng,
pháo hoa + confetti khi mở thư, đoạn thư hiện dần, tiêu đề ánh hồng, ảnh nghiêng 3D theo chuột, lightbox chuyển ảnh ← →,
vệt lấp lánh theo con trỏ, pháo hoa nhỏ khi bấm ra ngoài. Tôn trọng `prefers-reduced-motion`.

## Chạy
Mở `index.html`, hoặc `python3 -m http.server` rồi vào http://localhost:8000. Deploy tĩnh được lên GitHub Pages / Vercel.
