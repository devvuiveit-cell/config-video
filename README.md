# LVC Muse — bản cập nhật

Repo này CHỈ chứa bản phát hành của LVC Muse để các bản đã cài tự cập nhật (không có mã nguồn).

- `latest.json`: bản mới nhất, có chữ ký ECDSA (tool kiểm chữ ký trước khi cài).
- `releases/<phiên bản>/lvc-muse.exe`: file chạy của từng bản.

Phát hành bằng `scripts/publish-update.ps1` trong repo mã nguồn. Không sửa tay `latest.json`: sửa tay làm hỏng chữ ký, mọi bản đã cài sẽ từ chối bản đó.
