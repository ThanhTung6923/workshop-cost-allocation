---
title : "Các bước dừng (Stop) hoặc chấm dứt (Terminate) EC2 Instance"
date: "2025-07-30"
weight : 2
chapter : false
pre : " <b> 7.2 </b> "
---
**7.2. Các bước dừng (Stop) hoặc chấm dứt (Terminate) EC2 Instance**

Trong Lab này, chúng ta đã tạo một EC2 Instance. Bạn có hai lựa chọn chính để xử lý nó:

1.  **Dừng (Stop) EC2 Instance:**
    * **Mục đích:** Ngừng phát sinh chi phí cho thời gian hoạt động của Instance. Instance sẽ chuyển sang trạng thái `stopped`. Bạn vẫn giữ được cấu hình và dữ liệu của Instance để khởi động lại sau này nếu cần.
    * **Lưu ý:** Bạn vẫn có thể bị tính phí cho **dung lượng lưu trữ EBS** (ổ đĩa gắn vào Instance) ngay cả khi Instance đã dừng, mặc dù phí này thường rất nhỏ và có thể nằm trong hạn mức Free Tier.
    * **Cách thực hiện:**
        * Trong AWS Console, truy cập **`EC2 Dashboard > Instances`**.
        * Tìm và chọn Instance bạn đã tạo (ví dụ: `Web-Server-Dev-001`).
        * Click vào nút **`Instance state`** ở phía trên cùng của bảng.
        * Trong menu thả xuống, chọn **`Stop instance`**.
        ![Ảnh 7.2.1: Menu "Instance state" trong EC2 Instances với tùy chọn "Stop instance" được highlight](/workshop-cost-allocation/images/anh-7/anh-7.2.1.png)
        * Xác nhận hành động khi được hỏi.

2.  **Chấm dứt (Terminate) EC2 Instance:**
    * **Mục đích:** Ngừng hoàn toàn tất cả các chi phí liên quan đến Instance đó (bao gồm cả EBS volume) từ thời điểm bạn chấm dứt. Instance sẽ bị xóa vĩnh viễn khỏi tài khoản của bạn.
    * **Lưu ý quan trọng:** Khi bạn chấm dứt một Instance, nó và tất cả dữ liệu trên ổ đĩa gốc của nó sẽ bị xóa vĩnh viễn và **không thể khôi phục**. Chỉ sử dụng tùy chọn này nếu bạn chắc chắn không cần Instance đó nữa.
    * **Cách thực hiện:**
        * Trong AWS Console, truy cập **`EC2 Dashboard > Instances`**.
        * Tìm và chọn Instance bạn đã tạo.
        * Click vào nút **`Instance state`** ở phía trên cùng của bảng.
        * Trong menu thả xuống, chọn **`Terminate instance`**.
        ![Ảnh 7.2.2: Menu "Instance state" trong EC2 Instances với tùy chọn "Terminate instance" được highlight](/workshop-cost-allocation/images/anh-7/anh-7.2.2.png)
        * Xác nhận hành động khi được hỏi.

**Khuyến nghị:**
Đối với mục đích của Lab này, nếu bạn đã hoàn thành việc khám phá và không cần Instance đó nữa, **`Terminate instance`** là lựa chọn tốt nhất để đảm bảo không có chi phí phát sinh thêm.
