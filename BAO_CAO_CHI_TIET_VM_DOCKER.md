# PHẦN 1 GIỚI THIỆU

- **Đặt vấn đề:** Lý do nghiên cứu về sự khác biệt giữa VM và Docker.
- **Mục tiêu:** Xác định các lợi ích và hạn chế của từng công nghệ.
- **Phạm vi:** Nghiên cứu sâu về kiến trúc bên trong và hiệu quả vận hành.

# PHẦN 2 CƠ SỞ LÝ THUYẾT

- **Kiến trúc VM chi tiết:** Mô tả công nghệ máy ảo, phần mềm ảo hóa.
- **Kiến trúc Docker chi tiết:** Cách Docker hoạt động, so sánh với VM.
- **System Calls:** clone, unshare, mount.
- **Namespaces:** Giải thích cách Docker sử dụng namespaces.
- **cgroups:** Quản lý tài nguyên hệ thống.
- **UnionFS:** Cấu trúc file hệ thống cho Docker.

# PHẦN 3 THIẾT KẾ VÀ HIỆN THỰC

- **Kiến trúc thực nghiệm:** Sơ đồ các thành phần.
- **Công cụ sử dụng:** Danh sách phần mềm và công nghệ.
- **Các bước triển khai chi tiết:**
  - VirtualBox Ubuntu Nginx.
  - Docker setup: Cài đặt và cấu hình Docker container.

# PHẦN 4 KẾT QUẢ VÀ KIỂM THỬ

- **Thời gian khởi động:** VM 40s vs Docker 1s.
- **Dung lượng:** VM 4.5GB vs Docker 54MB.
- **RAM idle:** VM 600MB vs Docker 12MB.
- **CPU idle:** VM 0.3% vs Docker 0.01%.
- **Requests per second:** VM 1176 vs Docker 2487.
- **Response time:** VM 8.5ms vs Docker 4.0ms.
- **Biểu đồ so sánh:** Hình ảnh biểu đồ.
- **Test cô lập:** PID Namespace, Network Isolation, Memory cgroups.

# PHẦN 5 KẾT LUẬN

- **Kết quả đạt được:** Tổng kết các điểm mạnh và yếu của công nghệ.
- **Giải thích kết quả:** Phân tích lý do kết quả đạt được.
- **Hạn chế:** Những vấn đề gặp phải trong quá trình nghiên cứu.
- **Hướng phát triển:** Đề xuất mở rộng nghiên cứu.

# TÀI LIỆU THAM KHẢO

- Danh sách tài liệu và nguồn tham khảo đã sử dụng.

# PHỤ LỤC

- **Cấu hình chi tiết:** Thông số cấu hình phần mềm và phần cứng.
- **Script thực nghiệm:** Các script đã sử dụng trong nghiên cứu.
- **File cấu hình Nginx:** Cấu hình chi tiết cho Nginx.