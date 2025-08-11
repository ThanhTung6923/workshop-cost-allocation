---
title : "Hiểu về No tag key và dữ liệu chưa cập nhật"
date: "2025-07-30"
weight : 5
chapter : false
pre : " <b> 6.4 </b> "
---
**6.5. Hiểu về No tag key và dữ liệu chưa cập nhật**

* **"No tag key: [Tên thẻ]"**: Khi bạn nhóm theo một thẻ (ví dụ: `Tag:Department`), nếu có chi phí phát sinh từ các tài nguyên **không được gắn thẻ `Department`** hoặc từ các loại chi phí **không thể gắn thẻ trực tiếp** (ví dụ: chi phí hỗ trợ AWS, một số loại phí truyền dữ liệu), thì các chi phí đó sẽ được nhóm lại dưới nhãn "No tag key: Department". Mục tiêu của bạn là giảm thiểu chi phí trong nhóm "No tag key" này bằng cách gắn thẻ đầy đủ cho tài nguyên.
    ![Ảnh 6.5.1: Phần "No tag key: Department" trong báo cáo Cost Explorer khi có chi phí không được gắn thẻ](/workshop-cost-allocation/images/anh-6/anh-6.5.1.png)
* **Dữ liệu chưa cập nhật:** Dữ liệu chi phí trong Cost Explorer không phải là thời gian thực. Sau khi các thẻ được kích hoạt, có thể mất một thời gian (vài giờ đến 24-48 giờ) để dữ liệu cập nhật đầy đủ. Nếu bạn chưa thấy con số mong muốn ngay lập tức, hãy kiên nhẫn và kiểm tra lại sau.
