---
title : "Tạo và Xác nhận trạng thái AWS Organizations"
date: "2025-07-30"
weight : 2
chapter : false
pre : " <b> 2.2 </b> "
---

**2.2. Tạo và Xác nhận trạng thái AWS Organizations**

AWS Organizations là dịch vụ cho phép bạn quản lý tập trung nhiều tài khoản AWS.  
Nếu tài khoản của bạn chưa có Organization, hãy thực hiện các bước dưới đây để tạo mới.

**Bước 1: Đăng nhập AWS Management Console**  
- Mở trình duyệt và truy cập: [https://console.aws.amazon.com](https://console.aws.amazon.com)  
- Đăng nhập bằng tài khoản AWS bạn muốn làm **Management Account** (tài khoản quản lý).  
- Đảm bảo bạn đang ở **Region** bất kỳ (Organizations là dịch vụ toàn cầu).  

![Màn hình đăng nhập AWS](/workshop-cost-allocation/images/anh-2/anh-2.2.1.png)

---

**Bước 2: Mở dịch vụ AWS Organizations**  
- Trong thanh tìm kiếm ở góc trên cùng, gõ **"Organizations"** và nhấn **Enter**.  
- Chọn dịch vụ **AWS Organizations** từ danh sách kết quả.  

![Thanh tìm kiếm AWS với từ khóa "Organizations"](/workshop-cost-allocation/images/anh-2/anh-2.2.2.png)

---

**Bước 3: Bắt đầu tạo Organization**  
- Nếu đây là lần đầu bạn vào dịch vụ này, AWS sẽ hiển thị nút **"Create an organization"**.  
- Nhấn **"Create an organization"**.  
- Chọn **"Enable all features"** để có đầy đủ tính năng quản lý và bảo mật (**khuyến nghị**).  

![Nút "Create an organization" và tùy chọn "Enable all features"](/workshop-cost-allocation/images/anh-2/anh-2.2.3.png)

---

**Bước 4: Chờ AWS khởi tạo Organization**  
- AWS sẽ tự động tạo **Root Organizational Unit (OU)**.  
- Tài khoản của bạn sẽ trở thành **Management Account** và được liệt kê dưới **Root OU**.  
- Bạn sẽ thấy thông báo:  
  `"You successfully created an AWS organization."`  

![Giao diện Dashboard AWS Organizations sau khi tạo thành công](/workshop-cost-allocation/images/anh-2/anh-2.2.4.png)

