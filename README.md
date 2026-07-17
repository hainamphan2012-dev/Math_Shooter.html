# 🌌 Math Universe 8: Vừa Học Vừa Chơi Toán Lớp 8

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://html.spec.whatwg.org/)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#)
[![Obsidian](https://img.shields.io/badge/Obsidian-7C4DFF?style=for-the-badge&logo=obsidian&logoColor=white)](https://obsidian.md/)
[![License](https://img.shields.io/badge/License-MIT-green.svg?style=for-the-badge)](#)

Chào mừng bạn đến với **Math Universe 8** — Hệ sinh thái học tập và ôn tập môn Toán Lớp 8 kết hợp phương pháp Game hóa (Gamification) độc đáo. Dự án này được thiết kế nhằm giúp học sinh ôn thi giữa kì 1 và chuẩn bị thuyết trình môn Toán một cách trực quan, hứng thú và không lo bị quá tải.

---

## 🎮 Các Trải Nghiệm Học Tập Tương Tác

Dự án bao gồm 3 ứng dụng web chạy offline cực kỳ đẹp mắt được tích hợp sẵn:

### 1. 🚀 Galaxy Math Defender (Chiến Binh Không Gian)
*   **Đường dẫn file:** `index.html` (GitHub Pages: trang chính)
*   **Thể loại:** Bắn súng không gian 2D cổ điển (Space Invaders style).
*   **Cách chơi:** Người chơi điều khiển phi thuyền di chuyển ngang, đọc câu hỏi hiển thị và ngắm bắn chính xác vào thiên thạch mang chữ cái đáp án đúng (A, B, C, hoặc D). Bắn trúng đáp án đúng sẽ nổ thiên thạch và nhận XP; bắn sai hoặc để va chạm sẽ làm hao tổn giáp phi thuyền (HP).

### 2. ⛰️ Math Quest (Chinh Phục Đỉnh Olympus)
*   **Đường dẫn file:** `01_Projects/Math_Quest.html`
*   **Thể loại:** Trò chơi nhập vai học tập (RPG Study Game).
*   **Cách chơi:** Vượt qua các trạm thử thách Toán học trên đường leo lên đỉnh Olympus huyền thoại. Mỗi trạm tương ứng với một chủ đề kiến thức trọng tâm của môn Toán 8.

### 3. 📝 Chuyên Gia Khảo Thí (Hệ thống Quiz thông minh)
*   **Đường dẫn file:** `01_Projects/Math_Quiz.html`
*   **Thể loại:** Hệ thống trắc nghiệm kiểm tra kiến thức đa chế độ.
*   **Tính năng:** Chế độ sáng/tối (Light/Dark mode) linh hoạt, hệ thống đếm giờ, chấm điểm tự động và tích hợp Trợ lý ảo giải thích chi tiết từng bước cho mỗi câu hỏi sau khi hoàn thành ván đấu.

---

## 📅 Sổ Tay Quản Lý Dự Án (Obsidian)

Ngoài phần game, dự án còn tích hợp các ghi chú quản lý theo phương pháp khoa học để lập kế hoạch ôn tập và thuyết trình:
*   📋 **[ON THI GIUA KI 1 TOAN.md](file:///d:/obsidian/obsidian%20123/01_Projects/ON%20THI%20GIUA%20KI%201%20TOAN.md):** Bản kế hoạch phân bổ thời gian hàng tuần để ôn lý thuyết (7 hằng đẳng thức, định lý Pythagore) và làm đề minh họa.
*   📢 **[THUYET TRINH TOAN.md](file:///d:/obsidian/obsidian%20123/01_Projects/THUYET%20TRINH%20TOAN.md):** Dàn ý chi tiết cho bài thuyết trình nhóm về *"Ứng dụng định lý Pythagore trong thực tế"*.

---

## 🛠️ Công Nghệ Sử Dụng

Dự án được xây dựng 100% bằng các công nghệ frontend thuần, chạy trực tiếp trên trình duyệt mà không cần cài đặt môi trường phức tạp:

*   **Ngôn ngữ chính:** HTML5 (Cấu trúc nội dung) & CSS3 (Giao diện vũ trụ Neon, phong cách Fantasy, chế độ tối/sáng mượt mà).
*   **Xử lý Logic & Đồ họa:** JavaScript thuần (Vanilla JS) kết hợp với **Canvas API** để vẽ các thực thể game 2D với tốc độ 60 FPS.
*   **Quản lý ghi chú:** Obsidian & Markdown để liên kết các chủ đề kiến thức.

---

## 📁 Cấu Trúc Thư Mục Dự Án

Thư mục được tổ chức theo cấu trúc quản lý thông tin PARA gọn gàng:

```text
Math_Universe_8/
├── .obsidian/               # Cấu hình cài đặt của ứng dụng ghi chú Obsidian
├── 01_Projects/             # Thư mục chính chứa tài nguyên game và kế hoạch
│   ├── index.html           # Game bắn súng Galaxy Math Defender (trang chính)
│   ├── Math_Quest.html      # Game nhập vai Chinh Phục Olympus
│   ├── Math_Quiz.html       # Hệ thống thi thử trắc nghiệm Toán 8
│   ├── ON THI GIUA KI 1.md  # Kế hoạch học tập hàng ngày
│   └── THUYET TRINH TOAN.md # Dàn ý bài thuyết trình Pythagore
├── 02_Areas/                # Lưu trữ tài liệu học tập các môn khác (nếu có)
├── 03_Resources/            # Tài nguyên tham khảo, công thức, đề thi
├── 04_Archives/             # Nơi cất giữ các bài tập, nhiệm vụ đã hoàn thành
└── README.md                # File giới thiệu dự án (bạn đang đọc)
```

---

## 🚀 Hướng Dẫn Sử Dụng Nhanh

Bạn có thể chạy dự án này trên máy tính cá nhân chỉ trong vài giây:

1.  **Tải mã nguồn** về máy hoặc nhân bản (clone) repo này:
    ```bash
    git clone https://github.com/username/math-universe-8.git
    ```
2.  **Mở Game:** Điều hướng vào thư mục và **click đúp chuột** vào `index.html` (Galaxy Math Defender), `Math_Quest.html`, hoặc `Math_Quiz.html` để chơi trực tiếp trên trình duyệt (Chrome, Edge, Firefox...).
3.  **Quản lý Tiến Độ:** Mở thư mục này bằng ứng dụng **Obsidian** để xem và tích chọn các việc cần làm trong các file `.md`.

---

⭐ **Hãy để lại 1 Star nếu bạn yêu thích dự án học tập thú vị này nhé!** Chúc các bạn ôn thi thật tốt và đạt điểm cao!
