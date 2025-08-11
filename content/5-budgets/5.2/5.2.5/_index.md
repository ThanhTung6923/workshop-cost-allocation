---
title : "Cấu hình Cảnh báo"
date: "2025-07-30"
weight : 5
chapter : false
pre : " <b> 5.2.5 </b> "
---
**5.2.5. Cấu hình Cảnh báo**

Đây là nơi bạn xác định khi nào và ai sẽ nhận được thông báo khi chi phí đạt đến ngưỡng.

1.  Click **`Add an alert threshold`**.
2.  **Threshold:**
    * Nhập một tỷ lệ phần trăm của ngân sách (ví dụ: `80%`) hoặc một số tiền cụ thể (ví dụ: `8` USD nếu ngân sách là 10 USD).
    * **Alert type:** Chọn `Actual` (cảnh báo khi chi phí thực tế đạt ngưỡng) hoặc `Forecasted` (cảnh báo khi chi phí dự kiến đạt ngưỡng - đây là một tùy chọn rất hữu ích để phòng ngừa, giúp bạn hành động trước khi vượt ngân sách).
3.  **Email recipients:** Nhập địa chỉ email của bạn để nhận cảnh báo. Bạn có thể nhập nhiều địa chỉ, phân cách bằng dấu phẩy.
4.  **Amazon SNS topic (tùy chọn nâng cao):** Nếu bạn muốn cảnh báo được gửi đến một hệ thống khác (ví dụ: Slack, Microsoft Teams, hoặc kích hoạt một AWS Lambda function để tự động hóa), bạn có thể cấu hình một SNS topic tại đây. Đối với Lab này, bạn có thể bỏ qua tùy chọn này và chỉ tập trung vào cảnh báo email.
    * **[Ảnh 5.2.5: Phần "Alerts" với Threshold và Email recipients được cấu hình]**
    ![Ảnh 5.2.5: Phần "Alerts" với Threshold và Email recipients được cấu hình](/workshop-cost-allocation/images/anh-5/anh-5.2.5.png)

