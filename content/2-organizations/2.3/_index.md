---
title : "Tạo Organizational Unit trong Root"
date: "2025-07-30"
weight : 3
chapter : false
pre : " <b> 2.3 </b> "
---

**2.3. Tạo Organizational Unit (OU) trong Root**

Trong ví dụ này, chúng ta sẽ tạo một cấu trúc OU như sau:  
- **Business-Units-OU** (Root chính)  
  - **Engineering-OU** (OU con)  

---

**Bước 1: Mở AWS Organizations**  
- Đăng nhập AWS Management Console bằng **Management Account**.  
- Truy cập dịch vụ **AWS Organizations**.  

![Mở AWS Organizations](/workshop-cost-allocation/images/anh-2/anh-2.3.1.png)

---

**Bước 2: Tạo Root OU "Business-Units-OU"**  
- Trong tab **"Organize accounts"**, chọn **Root** mặc định.  
- Nhấn **"Create organizational unit"**.  
- Nhập tên: `Business-Units-OU`.  
- Nhấn **Create**.  

![Tạo Business-Units-OU](/workshop-cost-allocation/images/anh-2/anh-2.3.2.png)

---

**Bước 3: Tạo OU con "Engineering-OU"**  
- Chọn **Business-Units-OU** vừa tạo.  
- Nhấn **"Create organizational unit"**.  
- Nhập tên: `Engineering-OU`.  
- Nhấn **Create**.  

![Tạo Engineering-OU](/workshop-cost-allocation/images/anh-2/anh-2.3.4.png)

---

**Kết quả**  
Cấu trúc OU sẽ như sau:  
- **Business-Units-OU**  
  - **Engineering-OU**  

![Cấu trúc OU](/workshop-cost-allocation/images/anh-2/anh-2.3.5.png)
