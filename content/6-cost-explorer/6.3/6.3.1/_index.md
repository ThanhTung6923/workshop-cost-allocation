---
title : "Điều chỉnh phạm vi thời gian"
date: "2025-07-30"
weight : 1
chapter : false
pre : " <b> 6.3.1 </b> "
---
**6.3.1. Điều chỉnh phạm vi thời gian**

* Ở góc trên bên phải của giao diện Cost Explorer, bạn sẽ thấy một ô chọn khoảng thời gian (ví dụ: "Last 6 months", "This month to date").
* **Rất quan trọng:** Chọn một khoảng thời gian **đủ dài** để bao gồm **thời gian EC2 Instance của bạn đã chạy và phát sinh chi phí**, cũng như thời gian bạn đã kích hoạt các thẻ phân bổ chi phí.
    * Click vào ô chọn ngày.
    * Các lựa chọn phổ biến:
        * **`Last 7 days` (7 ngày gần nhất):** Tốt nếu bạn mới chạy EC2 gần đây.
        * **`This month to date` (Từ đầu tháng đến nay):** Nếu Instance chạy trong tháng hiện tại.
        * **`Custom` (Tùy chỉnh):** Đây là lựa chọn tốt nhất để đảm bảo bạn bao quát toàn bộ thời gian. Click vào `Custom`, sau đó chọn ngày bạn khởi chạy EC2 Instance (ví dụ: ngày 16/7/2025) cho đến ngày hôm nay.
    ![Ảnh 6.3.1: Thanh chọn Date range trong Cost Explorer, hiển thị các tùy chọn và "Custom" được highlight](/workshop-cost-allocation/images/anh-6/anh-6.3.1.png)