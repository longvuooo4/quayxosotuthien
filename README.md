# Vé số yêu thương

Website quay số gây quỹ của CLB Karate-Do Đại học Duy Tân.

## Chạy website

Mở `dist/index.html` trong Chrome hoặc Edge. Không cần cài thư viện hay build.

## GitHub Pages

Trong repo, vào **Settings → Pages → Build and deployment → Source**, chọn **GitHub Actions**. Workflow `Deploy website to GitHub Pages` sẽ đưa thư mục `dist` lên Pages khi có commit mới trên `main`. Có thể chạy thủ công tại **Actions → Deploy website to GitHub Pages → Run workflow**.

## Chức năng

- Chọn 4 hoặc 5 chữ số, khoảng số đầu và cuối (bao gồm cả hai đầu).
- Cấu hình lượt quay theo từng giải; đặt 0 để bỏ qua giải.
- Quay từ khuyến khích đến giải ba, nhì, nhất, đặc biệt.
- Hé lộ từ phải sang trái; không lặp số trúng trong chương trình.
- Tổng lượt quay không được vượt số lượng số trong khoảng.

Kết quả chỉ giữ trong phiên trang hiện tại. Tải lại trang hoặc áp dụng thiết lập mới sẽ xóa kết quả.
