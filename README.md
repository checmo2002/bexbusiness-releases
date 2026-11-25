# BexBusiness · bản cập nhật

Repo này chỉ chứa các bản cập nhật của app **BexBusiness** (Powered by Beso) để app Windows tự kiểm tra và tải về. Không chứa mã nguồn.

- `latest.json`: thông tin bản mới nhất (phiên bản, đường dẫn, mã kiểm tra SHA-256)
- `server/<phiên bản>/`: gói máy chủ + giao diện (nhỏ, cập nhật thường xuyên)
- `shell/<phiên bản>/`: bộ cài đầy đủ, chia thành nhiều phần < 50 MB (chỉ khi phần vỏ app đổi)

App kiểm tra 20 giây sau khi mở và mỗi 3 giờ. Khi có bản mới, thanh tiêu đề hiện nút **Cập nhật**; nếu không bấm, app tự cập nhật khi mở lần sau.
