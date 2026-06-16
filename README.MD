# 📚 Algo Sharing Repository

Repo này được tạo ra với mục đích:

* 🧠 Chia sẻ lời giải thuật toán trong nhóm
* 👀 Học hỏi cách giải của nhau
* 🚀 Cùng nhau cải thiện kỹ năng code (C++ / Python)

---

## 📥 Cách clone repo

```bash
git clone https://github.com/anh-ton/algo-sharing.git
cd algo-sharing
```

---

## 🔄 Quy trình làm việc cơ bản

### 1. Lấy code mới nhất (pull)

```bash
git pull origin main
```

---

### 2. Thêm bài mới / sửa code

* Tạo thư mục theo **tên của bạn**
* Bên trong tạo thư mục theo **tên bài toán**

Ví dụ:

```
.
├── mr-ton
│   └── cot-nhieu-so-fibonacci-nhat
│       ├── de-bai.jpeg
│       └── main.cpp
```

---

### 3. Thêm file vào git

```bash
git add .
```

---

### 4. Commit

```bash
git commit -m "add: solution bai fibonacci"
```

---

### 5. Push lên repo

```bash
git push origin main
```

---

## 📁 Quy tắc tổ chức thư mục

Cấu trúc chuẩn:

```
repo/
├── <ten-ban>/
│   └── <ten-bai-toan>/
│       ├── de-bai.(png/jpg/pdf)   # (optional)
│       ├── main.cpp / main.py
│       └── note.txt (optional)
```

### 📌 Quy định:

* `ten-ban`: viết thường, không dấu (vd: `mr-ton`, `nguyen-a`)
* `ten-bai-toan`: viết thường, dùng `-` thay cho khoảng trắng
  👉 ví dụ: `cot-nhieu-so-fibonacci-nhat`
* Mỗi bài 1 folder riêng
* Có thể thêm:

  * `de-bai` (ảnh đề)
  * `note.txt` (ghi chú ý tưởng)

---

## 💡 Lưu ý

* Luôn `git pull` trước khi làm để tránh conflict
* Không sửa code của người khác nếu chưa trao đổi
* Code rõ ràng, dễ đọc để mọi người học được

---

## 🎯 Mục tiêu

* Không chỉ giải bài, mà còn **hiểu cách người khác nghĩ**
* Xây dựng một **kho thuật toán chung của team**

---

🔥 Chúc mọi người học tốt và code ngày càng xịn!
