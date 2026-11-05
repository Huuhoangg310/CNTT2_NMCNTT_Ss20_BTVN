# Ecommerce Project

Repository mau cho du an thuong mai dien tu. Cau truc duoc sap xep de tranh dua thong tin nhay cam len GitHub Public.

## Cau truc

- `src/`: Ma nguon ung dung.
- `config/`: Cau hinh du an.
- `tests/`: Ma kiem thu.
- `.env.example`: Mau cac bien moi truong Dev, Test va Production.
- `.gitignore`: Loai tru cac tep noi bo va tep chua thong tin bi mat.
- `SECURITY_REPORT.md`: Bao cao rui ro bao mat.

## Cach bat dau

1. Cai dat Node.js.
2. Cai dat thu vien: `npm install`.
3. Tao tep `.env` tu `.env.example`.
4. Dien gia tri that vao `.env` tren may ca nhan, khong commit tep nay.
5. Chay ung dung theo lenh trong `package.json`.

## Luu y bao mat

- Khong commit API Key, mat khau, token hoac du lieu khach hang.
- Bat 2FA cho tai khoan GitHub.
- Quet secret bang Gitleaks truoc khi push.
- Neu da lo secret, can thu hoi va tao lai secret; xoa tep khoi commit don thuan la chua du.
