# ⚡ DeFi Nexus

> Nền tảng tài chính phi tập trung (DeFi) thế hệ mới, được xây dựng hoàn toàn bằng **Native HTML5, CSS3 và JavaScript thuần túy** theo chuẩn Modern Web Guidance, tuyệt đối không sử dụng thư viện bên thứ ba.

---

## 🚀 Tính năng nổi bật

* **Kết nối ví Web3 đa nền tảng:** Hỗ trợ kết nối trực tiếp với **MetaMask** và **OKX Wallet** thông qua chuẩn EIP-1193 gốc của trình duyệt (`window.ethereum` & `window.okxwallet`).
* **Hiệu năng cực cao (High Performance):** Không tải các thư viện JavaScript hay CSS nặng nề (như React, Vue, Tailwind, Web3.js, ethers.js), giúp trang web tải tức thì.
* **Giao diện Modal gốc (`<dialog>` API):** Sử dụng thẻ `<dialog>` tiêu chuẩn của HTML5 để quản lý modal chọn ví, tích hợp sẵn tính năng tự động khóa tiêu điểm (`focus trapping`) và hỗ trợ phím `ESC` nguyên bản.
* **Khả năng tiếp cận (Accessibility - a11y):** Tối ưu hóa điều hướng bằng bàn phím với `:focus-visible` và các thuộc tính ARIA đầy đủ (`aria-haspopup`, `aria-labelledby`).
* **Quản lý sự kiện chuỗi (Chain & Account Events):** Tự động cập nhật giao diện khi người dùng thay đổi tài khoản hoặc chuyển đổi mạng lưới (Network) trên ví.

---

## 🛠️ Công nghệ sử dụng

* **HTML5:** Semantic HTML (`<header>`, `<main>`, `<section>`, `<article>`, `<dialog>`).
* **CSS3:** Native CSS Variables (`:root`), CSS Grid, Flexbox, Dark Mode mặc định.
* **JavaScript (ES Modules):** Vanilla JS, EIP-1193 Provider API.

---

## 📦 Cài đặt và Chạy thử

Vì dự án **không sử dụng bất kỳ thư viện hay công cụ build nào (No build tools)**, bạn có thể chạy ứng dụng trực tiếp cực kỳ đơn giản:

1. Tải hoặc sao chép toàn bộ mã nguồn vào một file có tên `index.html`.
2. Mở file `index.html` trực tiếp bằng bất kỳ trình duyệt hiện đại nào (Google Chrome, Brave, Edge) đã cài sẵn tiện ích mở rộng ví **MetaMask** hoặc **OKX Wallet**.
3. *(Khuyên dùng)* Để có trải nghiệm tốt nhất với ES Modules hoặc môi trường Localhost, bạn có thể chạy bằng **VS Code Live Server** hoặc chạy nhanh qua Python:
   ```bash
   python -m http.server 8000
