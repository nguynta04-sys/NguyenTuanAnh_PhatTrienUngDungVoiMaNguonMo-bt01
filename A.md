A. Đăng ký tên miền xịn cho cá nhân:

-1: Đăng kí domain thành công!!

<img width="1916" height="1073" alt="image" src="https://github.com/user-attachments/assets/af467bbe-35a0-4e69-aabd-ec1bb6e9de15" />


2: Đăng ký tài khoản cloudflare 

-Sau khi đã sở hữu tên miền teumagic.io.vn, ta tiến hành các bước cấu hình ở Cloudflare, đây là bước quan trọng để đưa ứng dụng ra thế giới 🌍.

Mục đích

-Việc trỏ Nameserver (NS) thực chất là chuyển quyền quản lý các bản ghi DNS từ nhà đăng ký (ví dụ: Mắt Bão, tenten) sang cho Cloudflare.

3. Cấu hình tên miền trên Cloudflare và Lấy Nameserver của Cloudflare

-Tại đây này, Cloudflare sẽ cung cấp cho bạn 2 dòng Nameserver:

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c4bf778a-1eb8-4c99-8f8f-b793f5cadc94" />

4. Thay đổi Nameserver tại nhà đăng ký

-Đăng nhập vào trang quản trị tên miền teumagic.io.vn

Vào mục:

-Quản lý tên miền

<img width="1920" height="1068" alt="image" src="https://github.com/user-attachments/assets/d9d341b4-de3f-41e1-8e8b-2f631fc2cca1" />

-Cấu hình DNS hoặc Thay đổi Nameserver

-Chọn chế độ: Custom Nameserver (Nameserver tùy chỉnh)

-Xóa các Nameserver cũ

-Dán 2 dòng Nameserver của Cloudflare vào:

<img width="1919" height="1080" alt="image" src="https://github.com/user-attachments/assets/152c9069-fe99-40a0-9803-db9b3fbd6d58" />

Kiểm tra và chờ cập nhật

-Quay lại Cloudflare → nhấn Check nameservers

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/7b4336ca-458e-4130-bb8d-09d03d32abba" />

