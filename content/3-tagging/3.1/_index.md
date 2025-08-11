---
title : "Khởi chạy EC2 Instance và gắn thẻ chi tiết"
date: "2025-07-30"
weight : 1
chapter : false
pre : " <b> 3.1 </b> "
---
**3.1. Tại sao cần gắn thẻ cho tài nguyên AWS?**

* **Phân bổ chi phí chính xác:** Đây là mục tiêu chính của Lab này. Bằng cách gắn thẻ `Department`, `Project`, `Environment`, bạn có thể dễ dàng xác định chi phí của từng đơn vị hoặc mục đích cụ thể.
* **Quản lý tài nguyên:** Dễ dàng tìm kiếm, lọc và nhóm các tài nguyên dựa trên thẻ. Ví dụ, bạn có thể nhanh chóng tìm tất cả các máy chủ thuộc về "Dự án X" trong môi trường "Sản xuất".
* **Kiểm soát truy cập:** Sử dụng thẻ trong các chính sách IAM (Identity and Access Management) để kiểm soát ai có thể truy cập hoặc thực hiện hành động trên các tài nguyên cụ thể.
* **Tự động hóa:** Tự động hóa các tác vụ quản lý và vận hành dựa trên thẻ, ví dụ: tự động dừng các máy chủ "Development" vào cuối ngày làm việc.
* **Tuân thủ:** Đảm bảo tài nguyên tuân thủ các quy tắc gắn thẻ của tổ chức.