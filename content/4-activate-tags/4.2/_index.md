---
title : "Các bước kích hoạt thẻ"
date: "2025-07-30"
weight : 2
chapter : false
pre : " <b> 4.2 </b> "
---
**4.2. Các bước kích hoạt thẻ**

1.  **Đăng nhập vào AWS Console:** Đảm bảo bạn đang đăng nhập vào tài khoản AWS hiện tại của bạn (tài khoản quản lý: `851920544845`).

2.  **Truy cập Billing Dashboard:**
    * Trên thanh điều hướng của AWS Console (thường là ở phía trên cùng của trang), click vào tên tài khoản của bạn (ví dụ: `Account ID: 851920544845`).
    * Trong menu thả xuống, chọn **`Billing Dashboard`**. Đây là trung tâm quản lý chi phí của bạn.
    ![Ảnh 4.2.1: Thanh điều hướng AWS Console với dropdown tài khoản và "Billing Dashboard](/workshop-cost-allocation/images/anh-4/anh-4.2.1.png)

3.  **Điều hướng đến "Cost allocation tags":**
    * Trong thanh điều hướng bên trái của Billing Dashboard, cuộn xuống mục **`Cost Organization`**.
    * Click vào **`Cost allocation tags`**.
    ![Ảnh 4.2.2: Thanh điều hướng Billing Dashboard với "Cost allocation tags" được highlight](/workshop-cost-allocation/images/anh-4/anh-4.2.2.png)
4.  **Kích hoạt các thẻ tùy chỉnh của bạn:**
    * Trên trang Cost Allocation Tags, bạn sẽ thấy hai tab: **`User-defined cost allocation tags`** và `AWS-generated cost allocation tags`.
    * Đảm bảo bạn đang ở tab **`User-defined cost allocation tags`**. Tab này hiển thị các khóa thẻ mà bạn hoặc các người dùng khác đã gắn vào tài nguyên của mình.
    * **Lúc này, bạn sẽ thấy các khóa thẻ mà bạn đã gắn cho EC2 Instance của mình (ví dụ: `Name`, `Department`, `Project`, `Environment`, `CostCenter`, `Owner`) xuất hiện trong danh sách này.** Nếu bạn chưa thấy, vui lòng xem lại phần 4.3. [Hiểu về thời gian chờ đợi dữ liệu](/workshop-cost-allocation/4-active-tags/4.3).
    * **Chọn ô vuông (checkbox)** bên cạnh **TẤT CẢ** các khóa thẻ này để kích hoạt chúng.
    ![Ảnh 4.2.3: Trang Cost Allocation Tags với các thẻ tùy chỉnh được chọn và nút "Activate" được highlight](/workshop-cost-allocation/images/anh-4/anh-4.2.3.png)
    * Sau khi chọn, nút màu xanh dương **`Activate`** ở góc trên bên phải của bảng sẽ sáng lên.
    * Click vào nút **`Activate`**.
    * Một hộp thoại xác nhận có thể xuất hiện, hỏi bạn có chắc chắn muốn kích hoạt các thẻ này không. Hãy xác nhận việc kích hoạt.
    * **Kiểm tra trạng thái:** Sau khi kích hoạt, trạng thái của các thẻ này sẽ chuyển từ **`Inactive`** sang **`Active`**. Bạn cũng sẽ thấy cột "Last updated date" được cập nhật, cho biết thời điểm thẻ được kích hoạt.
    ![Ảnh 4.2.4.2: Các thẻ đã được kích hoạt thành công, hiển thị trạng thái "Active"](/workshop-cost-allocation/images/anh-4/anh-4.2.4.png)
