# Web/app học tập — Hóa học 9, Bài 35

**Bài 35: Khai thác nhiên liệu hoá thạch**
Môn Khoa học tự nhiên 9 (phân môn Hóa học) — Chương trình GDPT 2018, sách Kết nối tri thức với cuộc sống. Chương X. Khai thác tài nguyên từ vỏ Trái Đất.

Giáo viên: Lê Văn Thắng — Trường TH và THCS Phước Hưng, xã Nhơn Hội, tỉnh An Giang.

## Nội dung

Web/app học tập 6 phần: Khởi động, Khám phá, Mô phỏng, Sơ đồ tư duy, Luyện tập (10 câu trắc nghiệm tự chấm), Vận dụng.

Bài 35 không có thí nghiệm hoá học trong SGK nên phần Mô phỏng là 3 hoạt động khám phá trực quan (không gọi là thí nghiệm), đều có hình minh họa SVG nội tuyến:
1. So sánh năng suất toả nhiệt — biểu đồ cột tương tác (gỗ 15–20 kJ/g, than đá 20–30 kJ/g, dầu hoả 42–45 kJ/g).
2. Phương trình đốt cháy tương tác — đếm số nguyên tử hai vế (CH4 + 2O2 → CO2 + 2H2O; C + O2 → CO2; C2H5OH + 3O2 → 2CO2 + 3H2O).
3. Sơ đồ chu trình carbon và hiệu ứng nhà kính dạng SVG tương tác.

Đáp án trắc nghiệm: 1C 2A 3C 4A 5D 6D 7B 8C 9B 10A.

## Cách dùng

- Mở file `index.html` bằng trình duyệt bất kì (không cần máy chủ).
- Học sinh đăng nhập bằng Họ tên + Lớp, học 6 phần, làm 10 câu trắc nghiệm rồi nộp bài.
- Điểm cao nhất lưu trên máy học sinh (localStorage).

## Google Sheets kết quả

- Sheet: https://docs.google.com/spreadsheets/d/1KU-c1arLbS7vtQIfOKjne2PlknUx3LwHGSu8ICK8kvs/edit
- **/exec chưa có — sẽ patch sau.** File `index.html` hiện KHÔNG chứa fetch Sheets. Khi có link /exec của Apps Script, patch thêm fetch gửi điểm về Sheet (tab KetQua) rồi đẩy lại GitHub/Vercel.

## File trong repo

- `index.html` — web/app hoàn chỉnh, tự chứa (hình ảnh nhúng base64).
- `Web_Hoc_Tap_Hoa9_Bai35.md` — bản sao toàn bộ mã nguồn kèm khóa đáp án.
- `Code.gs` — Apps Script Web App ghi điểm về Google Sheets (tab KetQua).
- `assets-flow/` — 3 ảnh nền gốc (JPG 1376×768) + logo cá nhân của Thầy.
