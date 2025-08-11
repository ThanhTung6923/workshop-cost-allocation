---
title : "Cấu hình Chi tiết Ngân sách"
date: "2025-07-30"
weight : 3
chapter : false
pre : " <b> 5.2.3 </b> "
---
**5.2.3. Cấu hình Chi tiết Ngân sách**

1.  **Name:** Đặt tên có ý nghĩa cho ngân sách của bạn.
    * **Ví dụ:** `MonthlyEC2Budget` (nếu bạn muốn theo dõi chi phí EC2 hàng tháng) hoặc `OverallAWSMonthlyLimit` (nếu bạn muốn theo dõi tổng chi phí tài khoản).
2.  **Period:** Chọn tần suất mà ngân sách của bạn sẽ được đánh giá.
    * Chọn **`Monthly`** (Hàng tháng). Các lựa chọn khác bao gồm `Quarterly` (Hàng quý), `Annually` (Hàng năm), hoặc `Daily` (Hàng ngày).
3.  **Budget amount:** Nhập số tiền ngân sách bạn muốn đặt cho tháng.
    * **Ví dụ:** Nhập `10` (USD) nếu bạn muốn đặt một giới hạn thấp để thử nghiệm và nhận cảnh báo sớm.
4.  **Start date:** Để mặc định là ngày hiện tại.
5.  **End date (Optional):** Bạn có thể để trống nếu muốn ngân sách này lặp lại vô thời hạn vào mỗi kỳ (ví dụ: mỗi tháng). Nếu bạn muốn một ngân sách chỉ dùng một lần, hãy chọn ngày kết thúc.
![Ảnh 5.2.3: Phần "Budget details" với các thông tin Name, Period, Budget amount được điền](/workshop-cost-allocation/images/anh-5/anh-5.2.3.png)