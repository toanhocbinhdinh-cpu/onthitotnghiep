# Chấm Phiếu PHP

MVP nền tảng chấm phiếu trắc nghiệm tương tự Chấm Phiếu TN, xây bằng PHP 8.3 + SQLite + JavaScript PWA.

## Chạy nhanh

```powershell
php -S 127.0.0.1:8090 -t public
```

Mở `http://127.0.0.1:8090`.

MVP hiện có: đăng ký/đăng nhập, bài thi, đáp án, danh sách học sinh, nhập CSV, chấm thủ công có hỗ trợ ảnh/camera, tính điểm và xuất CSV. Phiếu chính hiện được lấy từ `public/assets/phieu-chinh.pdf`; tọa độ vùng OMR được mô tả trong `public/assets/phieu-template.json`. Phần OMR tự động cần bổ sung OpenCV.js/Web Worker trong sprint tiếp theo.


