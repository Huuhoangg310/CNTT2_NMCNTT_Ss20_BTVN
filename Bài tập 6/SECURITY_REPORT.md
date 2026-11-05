# Bao cao danh gia rui ro khi thieu .gitignore

## Muc dich

Danh gia nguy co khi dua ma nguon du an thuong mai dien tu len GitHub Public ma khong co tep `.gitignore`.

## Rui ro

1. Tep `.env` co the bi day len GitHub, lam lo API Key, mat khau va chuoi ket noi co so du lieu.
2. Hacker co the dung thong tin bi lo de truy cap dich vu hoac co so du lieu.
3. Tep log co the chua thong tin tai khoan, du lieu giao dich hoac loi he thong.
4. Tep build va thu muc thu vien lam repository nang va kho quan ly.
5. Tep cau hinh rieng cua may lap trinh vien co the bi chia se khong can thiet.

## Bien phap

- Tao `.gitignore` va loai tru `.env`, log, thu muc dependencies va build.
- Chi commit `.env.example` voi gia tri mau, khong chua secret that.
- Dung Gitleaks quet ma nguon truoc khi push.
- Bat 2FA cho tat ca thanh vien co quyen truy cap repository.
- Neu secret da tung duoc commit, thu hoi/rotate secret ngay; sua lich su Git neu can.

## Ket luan

Thieu `.gitignore` lam tang nguy co lo thong tin nhay cam va lam repository kem gon gang. Can kiem tra cac tep truoc khi cong khai ma nguon.
