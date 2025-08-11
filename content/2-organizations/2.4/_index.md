---
title : "Tạo AWS Account trong Organizational Unit"
date: "2025-07-30"
weight : 4
chapter : false
pre : " <b> 2.4 </b> "
---

**2.4. Tạo AWS Account trong Organizational Unit**

Trong ví dụ này, chúng ta sẽ tạo một AWS Account mới có tên **ProjectX-Dev-Account** và đặt nó vào **Engineering-OU**.

---

**Bước 1: Mở AWS Organizations**  
- Đăng nhập AWS Management Console bằng **Management Account**.  
- Truy cập dịch vụ **AWS Organizations**.  

![Mở AWS Organizations](/workshop-cost-allocation/images/anh-2/anh-2.3.1.png)

---

**Bước 2: Chọn OU "Engineering-OU"**  
- Trong **"Organize accounts"**, chọn **Business-Units-OU**.  
- Mở **Engineering-OU**.  

![Chọn Engineering-OU](/workshop-cost-allocation/images/anh-2/anh-2.4.1.png)

---

**Bước 3: Tạo AWS Account mới**  
- Trong **Engineering-OU**, nhấn **"Add an account"** → **"Create account"**.  
- Nhập:
  - **Account name**: `ProjectX-Dev-Account`  
  - **Email address**: Email chưa từng đăng ký AWS.  
- Nhấn **Create**.  

![Tạo ProjectX-Dev-Account](/workshop-cost-allocation/images/anh-2/anh-2.4.2.png)

---

**Bước 4: Xác nhận**  
- AWS sẽ gửi email kích hoạt tới địa chỉ email đã nhập.  
- Sau khi xác nhận, tài khoản sẽ hiển thị dưới **Engineering-OU**.  

![ProjectX-Dev-Account trong OU](/workshop-cost-allocation/images/anh-2/anh-2.4.3.png)
