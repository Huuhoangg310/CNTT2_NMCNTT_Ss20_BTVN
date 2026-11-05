# Pre-push Checklist

Truoc moi lan push len GitHub Public, kiem tra:

- [ ] Khong hardcode API Key, password, token hoac private key.
- [ ] Khong commit tep `.env` va cac tep cau hinh co secret.
- [ ] Chi commit `.env.example` voi gia tri mau.
- [ ] Da kiem tra `git status` va cac tep trong commit.
- [ ] Da quet secret bang Gitleaks.
- [ ] Da kiem tra ca lich su commit neu repository tung chua secret.
- [ ] Tat ca thanh vien da bat 2FA tren GitHub.
- [ ] Khong dua du lieu khach hang that len repository.

Lenh kiem tra co ban:

```bash
git status
git diff --cached
gitleaks detect --source . --verbose
```

Neu phat hien secret: dung push, thu hoi/rotate secret va lam sach commit truoc khi tiep tuc.
