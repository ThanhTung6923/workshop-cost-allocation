---
title : "Sử dụng Group by để phân bổ chi phí theo thẻ"
date: "2025-07-30"
weight : 2
chapter : false
pre : " <b> 6.3.2 </b> "
---
**6.3.2. Sử dụng "Group by" để phân bổ chi phí theo thẻ**

Đây là phần cốt lõi để bạn thấy chi phí được phân loại theo các thẻ mà bạn đã thiết lập.

* Ngay phía trên biểu đồ chính, bạn sẽ thấy một ô thả xuống có nhãn **`Group by`**.
* Click vào ô thả xuống đó.
* Trong danh sách các tùy chọn `Group by`, cuộn xuống tìm phần **`Tags`**.
* **Chọn một trong các thẻ tùy chỉnh của bạn mà bạn đã gắn cho EC2 Instance.**
    * **Ví dụ 1: Nhóm theo Phòng ban:** Chọn **`Tag:Department`**.
        * **Quan sát:** Cost Explorer sẽ tự động vẽ lại biểu đồ và sắp xếp lại bảng dữ liệu bên dưới để hiển thị chi phí của bạn được chia nhỏ theo từng giá trị mà thẻ `Department` của bạn có (ví dụ: `Marketing`, `Engineering`, v.v.). Nếu có chi phí không được gắn thẻ `Department`, chúng sẽ được nhóm dưới nhãn **"No tag key: Department"**.
        ![Ảnh 6.3.2.1: Giao diện Cost Explorer với dropdown "Group by" mở ra, hiển thị các tùy chọn Tag và "Tag:Department" được chọn](/workshop-cost-allocation/images/anh-6/anh-6.3.2.1.png)
        ![Ảnh 6.3.2.2: Biểu đồ và bảng "Cost and usage breakdown" trong Cost Explorer hiển thị chi phí được nhóm theo Tag:Department](/workshop-cost-allocation/images/anh-6/anh-6.3.2.2.png)
    * **Ví dụ 2: Nhóm theo Dự án:** Thay đổi `Group by` để chọn **`Tag:Project`**.
        * **Quan sát:** Biểu đồ và bảng sẽ hiển thị chi phí được nhóm theo từng dự án (ví dụ: `WebsiteLaunch`, `CRMSystem`).
    * **Ví dụ 3: Nhóm theo Môi trường:** Chọn **`Tag:Environment`**.
        * **Quan sát:** Biểu đồ và bảng sẽ hiển thị chi phí theo từng môi trường (`Development`, `Production`, v.v.).
    * **Nhóm hai cấp độ (Tùy chọn nâng cao):** Bạn có thể nhóm theo hai thẻ cùng lúc để có cái nhìn chi tiết hơn.
        * Đầu tiên, chọn **`Tag:Department`** cho "Group by" thứ nhất.
        * Sau đó, click lại vào ô "Group by" và chọn **`Tag:Project`** cho "Group by" thứ hai.
        * **Quan sát:** Biểu đồ và bảng sẽ hiển thị chi phí của từng dự án trong mỗi phòng ban, cung cấp một cái nhìn rất chi tiết.
