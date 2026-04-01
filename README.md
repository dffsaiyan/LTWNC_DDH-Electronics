# 🛒 DDH Electronics - Website Kinh doanh Linh kiện & Thiết bị Điện tử

> **Đồ án / Bài tập lớn Lập trình Web nâng cao**  
> Hệ thống thương mại điện tử hiện đại tích hợp AI, thanh toán trực tuyến và đăng nhập mạng xã hội.

---

## 👥 Thành viên nhóm

| STT | Họ và tên        | MSSV        | Vai trò      |
| --- | ---------------- | ----------- | ------------ |
| 1   | Nguyễn Đức Dương | 23810310091 | Nhóm trưởng  |
| 2   | Nguyễn Văn Đạt   | 23810310093 | Thành viên   |
| 3   | Nguyễn Văn Hiếu  | 23810310112 | Thành viên   |

---

## 🚀 Công nghệ sử dụng

| Thành phần | Công nghệ                                                |
| ---------- | -------------------------------------------------------- |
| **Backend**  | Laravel 11.x (PHP 8.2+), mô hình MVC                     |
| **Frontend** | Blade Template, CSS Vanilla, JavaScript, Vite            |
| **Database** | MySQL / MariaDB                                          |
| **Thanh toán**| Tích hợp cổng VNPay và MoMo (Sandbox)                    |
| **AI Support**| Tích hợp Groq AI (Llama 3.3) hỗ trợ khách hàng           |
| **Auth**     | Laravel Sanctum, Social Login (Google, Zalo)             |

---

## 🌟 Tính năng chính

### 👤 Khách hàng (User)
- Xem và tìm kiếm sản phẩm điện tử thông minh.
- Quản lý giỏ hàng, danh sách yêu thích (Wishlist).
- Đặt hàng và thanh toán trực tuyến qua VNPay/MoMo.
- Chat với trợ lý ảo AI để được tư vấn sản phẩm.
- Theo dõi trạng thái đơn hàng và lịch sử mua hàng.
- Đăng nhập nhanh qua Google hoặc Zalo.

### 🛠 Quản trị viên (Admin)
- Quản lý danh mục, sản phẩm và kho hàng.
- Quản lý đơn hàng, doanh thu và thống kê báo cáo.
- Quản lý người dùng và phản hồi của khách hàng.

---

## 🛠 Hướng dẫn cài đặt

1. **Clone project:**
   ```bash
   git clone https://github.com/dffsaiyan/LTWNC_DDH-Electronics.git
   ```

2. **Cài đặt dependencies:**
   ```bash
   composer install
   npm install && npm run dev
   ```

3. **Cấu hình môi trường:**
   - Sao chép `.env.example` thành `.env`
   - Cấu hình Database, Mail và các API Keys (VNPay, MoMo, Groq, Google/Zalo Client ID).

4. **Khởi tạo Database:**
   ```bash
   php artisan migrate --seed
   ```

5. **Chạy server:**
   ```bash
   php artisan serve
   ```

---

## 📝 Giấy phép
Dự án được thực hiện nhằm mục đích học tập.
