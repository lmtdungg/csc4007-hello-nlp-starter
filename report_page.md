## Lab0 – Setup & Hello NLP

**Pipeline:** TF-IDF vectorizer → LogisticRegression, dữ liệu random 300 samples (2 class), seed=42, split 80/20.
**Metrics:** accuracy=1.0, macro-F1=1.0, n_train=240, n_test=60.
**Vấn đề gặp:** conda không nhận trong PowerShell → dùng venv thay thế.
**Cách xử lý:** `python -m venv .venv`, chạy `Set-ExecutionPolicy RemoteSigned`, activate OK.
**Reproducibility:** seed=42 cố định trong code và pytest, chạy 2 lần kết quả không đổi.
**Giới hạn:** Dữ liệu random không phản ánh thực tế; TF-IDF mặc định bỏ 1-char token.
