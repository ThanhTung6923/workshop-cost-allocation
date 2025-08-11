---
title : "Cấu hình Phạm vi"
date: "2025-07-30"
weight : 4
chapter : false
pre : " <b> 5.2.4 </b> "
---
**5.2.4. Cấu hình Phạm vi**

Phần này cho phép bạn xác định ngân sách này sẽ áp dụng cho những chi phí nào.

1.  **Filter type:**
    * Để bắt đầu đơn giản và không phụ thuộc vào việc các thẻ tùy chỉnh của bạn đã xuất hiện đầy đủ trong Cost Explorer hay chưa, bạn có thể chọn:
        * **`All AWS services`**: Nếu bạn muốn ngân sách này áp dụng cho tổng chi phí của toàn bộ tài khoản AWS của bạn.
        * **`Service`**: Nếu bạn chỉ muốn theo dõi chi phí của một dịch vụ cụ thể (ví dụ: chỉ EC2). Click **`Add filter`**, chọn **`Service`** từ danh sách thả xuống, sau đó chọn **`EC2 - Elastic Compute Cloud`**.
        ![Ảnh 5.2.4: Phần "Scope" với filter "Service" và "EC2 - Elastic Compute Cloud" được chọn](/workshop-cost-allocation/images/anh-5/anh-5.2.4.png)
        * **`Linked account`**: (Bỏ qua cho Lab này vì bạn đang dùng tài khoản quản lý và chưa có tài khoản con).
    * **Lưu ý quan trọng về Tag:** Bạn **chưa** chọn **`Tag`** ở bước này nếu bạn đang tạo ngân sách ban đầu và đang chờ dữ liệu thẻ cập nhật trong Cost Explorer. Sau này, khi các thẻ (`Department`, `Project`, v.v.) đã "Active" và dữ liệu đã hiển thị trong Cost Explorer, bạn có thể quay lại chỉnh sửa ngân sách này để thêm bộ lọc theo thẻ. Điều này sẽ giúp bạn tạo các ngân sách chi tiết hơn cho từng phòng ban hoặc dự án cụ thể.