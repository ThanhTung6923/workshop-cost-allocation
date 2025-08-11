---
title : "Sử dụng Filters để tinh chỉnh báo cáo"
date: "2025-07-30"
weight : 3
chapter : false
pre : " <b> 6.3.3 </b> "
---
**6.3.3. Sử dụng Filters để tinh chỉnh báo cáo**

Phần "Filters" ở cột bên phải cho phép bạn thu hẹp phạm vi dữ liệu mà bạn muốn phân tích.

* Ở cột bên phải của giao diện Cost Explorer, dưới mục **`Filters`**, bạn sẽ thấy các tùy chọn như `Resource`, `Cost category`, `Tag`, v.v.
* **a. Lọc theo Dịch vụ (Service):**
    * Click vào **`Service`** ở cột bên phải.
    * Chọn **`EC2 - Elastic Compute Cloud`** từ danh sách.
    * **Mục đích:** Điều này sẽ lọc bỏ tất cả chi phí từ các dịch vụ AWS khác và chỉ hiển thị chi phí liên quan đến EC2 (nơi Instance của bạn đang chạy). Điều này hữu ích khi bạn muốn tập trung vào chi phí của một dịch vụ cụ thể.
    ![Ảnh 6.3.3.1: Cột "Filters" trong Cost Explorer với filter "Service" được mở và "EC2 - Elastic Compute Cloud" được chọn](/workshop-cost-allocation/images/anh-6/anh-6.3.3.1.png)
* **b. Lọc theo Tag cụ thể:**
    * Dưới mục "Tag" ở cột bên phải, bạn sẽ thấy các thẻ của mình đã được kích hoạt (ví dụ: `Department`, `Project`).
    * Click vào thẻ bạn muốn lọc, ví dụ **`Department`**.
    * Sổ ra danh sách các giá trị của thẻ `Department` (ví dụ: `Marketing`).
    * Chọn giá trị **`Marketing`**.
    * **Mục đích:** Báo cáo sẽ chỉ hiển thị chi phí liên quan đến các tài nguyên có thẻ `Department` là `Marketing`. Điều này hữu ích khi bạn muốn xem chi phí chỉ cho một phòng ban hoặc dự án cụ thể mà không cần xem toàn bộ dữ liệu.
    * Bạn có thể áp dụng nhiều bộ lọc cùng lúc để có báo cáo rất cụ thể (ví dụ: chi phí EC2 của bộ phận Marketing cho dự án Website Launch trong môi trường Development).
    ![Ảnh 6.3.3.2: Cột "Filters" trong Cost Explorer với filter "Department" được mở và giá trị "Marketing" được chọn](/workshop-cost-allocation/images/anh-6/anh-6.3.3.2.png)
