---
title : "Cấu hình các thiết lập cơ bản khác"
date: "2025-07-30"
weight : 4
chapter : false
pre : " <b> 3.2.4 </b> "
---
**3.2.4. Cấu hình các thiết lập cơ bản khác (AMI, Instance Type, Key Pair, Network, Storage)**

Sau khi đã cấu hình thẻ, bạn cần tiếp tục cấu hình các thông số kỹ thuật cho Instance của mình.

1.  **Application and OS Images (Amazon Machine Image - AMI):**
    * Chọn một AMI phù hợp với Free Tier để tránh phát sinh chi phí không mong muốn trong quá trình học tập.
    * **Ví dụ:** Chọn `Amazon Linux 2023 AMI (HVM) - Kernel 6.1` hoặc `Ubuntu Server 22.04 LTS`.
    * **[Ảnh 3.2.4.1: Phần chọn AMI trên trang Launch an instance]**
    ![Ảnh 3.2.4.1: Phần chọn AMI trên trang Launch an instance](/workshop-cost-allocation/images/anh-3/anh-3.2.4.1.png)
2.  **Instance type:**
    * Chọn một loại Instance đủ điều kiện cho Free Tier.
    * **Ví dụ:** Chọn `t2.micro` (hoặc `t3.micro`).
    ![Ảnh 3.2.4.2: Phần chọn Instance type trên trang Launch an instance với t2.micro được chọn](/workshop-cost-allocation/images/anh-3/anh-3.2.4.2.png)
3.  **Key pair (login):**
    * Key pair là cần thiết nếu bạn muốn kết nối SSH vào Instance sau này.
    * Chọn một cặp khóa hiện có từ danh sách thả xuống, hoặc click **`Create new key pair`** để tạo một cặp khóa mới và tải xuống file `.pem`.
    * **[Ảnh 3.2.4.3: Phần chọn Key pair trên trang Launch an instance]**
    ![Ảnh 3.2.4.3: Phần chọn Key pair trên trang Launch an instance](/workshop-cost-allocation/images/anh-3/anh-3.2.4.3.png)
4.  **Network settings:**
    * Đảm bảo `Auto-assign public IP` là `Enable` nếu bạn muốn Instance có địa chỉ IP công cộng để truy cập từ Internet.
    * **Firewall (Security group):** Security Group đóng vai trò là tường lửa ảo kiểm soát lưu lượng truy cập vào và ra khỏi Instance của bạn.
        * Chọn **`Create security group`**.
        * Đảm bảo **`Allow SSH traffic from the internet`** (Port 22 từ `0.0.0.0/0`) được chọn để bạn có thể kết nối SSH.
        * Nếu bạn dự định chạy một ứng dụng web, hãy chọn thêm **`Allow HTTP traffic from the internet`** (Port 80) và/hoặc **`Allow HTTPS traffic from the internet`** (Port 443).
        * Bạn có thể click **`Edit`** để tùy chỉnh các quy tắc Security Group chi tiết hơn.
    ![Ảnh 3.2.4.4: Phần Network settings với tùy chọn Auto-assign public IP và Security group rules](/workshop-cost-allocation/images/anh-3/anh-3.2.4.4.png)
5.  **Configure storage:**
    * Để mặc định 8 GiB là đủ cho mục đích của Lab này. Dung lượng này thường nằm trong hạn mức Free Tier cho EBS (Elastic Block Store).
    ![Ảnh 3.2.4.5: Phần Configure storage với dung lượng mặc định](/workshop-cost-allocation/images/anh-3/anh-3.2.4.5.png)
6.  **Xem lại Summary:**
    * Ở cột bên phải, bạn sẽ thấy một bản tóm tắt các cấu hình của Instance. Hãy kiểm tra lại một lần cuối.
    ![Ảnh 3.2.4.6: Cột Summary hiển thị tóm tắt cấu hình Instance trước khi khởi chạy](/workshop-cost-allocation/images/anh-3/anh-3.2.4.6.png)

