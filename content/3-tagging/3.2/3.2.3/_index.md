---
title : "Cấu hình Name and Tags"
date: "2025-07-30"
weight : 3
chapter : false
pre : " <b> 3.2.3 </b> "
---
**3.2.3. Cấu hình Name and Tags**

Đây là bước quan trọng nhất để áp dụng chiến lược gắn thẻ của bạn ngay từ đầu.

1.  **Mục "Name and tags":**
    * Ngay dưới tiêu đề "Launch an instance", bạn sẽ thấy phần **`Name and tags`**.
    * Trong ô **`Name`**, nhập tên mà bạn muốn hiển thị cho Instance này. Tên này sẽ tự động tạo ra một thẻ với Key là `Name` và Value là tên bạn nhập.
        * **Ví dụ:** Nhập `Web-Server-Dev-001`.
    ![Ảnh 3.2.3.1: Phần "Name and tags" trên trang Launch an instance, với ô Name được nhập và nút "Add additional tags" được highlight](/workshop-cost-allocation/images/anh-3/anh-3.2.3.1.png)

2.  **Thêm các thẻ phân bổ chi phí tùy chỉnh:**
    * Ngay bên cạnh ô "Name", click vào nút **`Add additional tags`**. Một bảng để thêm các cặp Key-Value cho thẻ sẽ xuất hiện.
    * Bạn sẽ thêm các thẻ sau đây. **Hãy chú ý đến việc viết hoa/thường (case-sensitive) của Key và Value để đảm bảo tính nhất quán.**
        * **Thẻ 1 (Phòng ban chịu trách nhiệm):**
            * **Key:** `Department`
            * **Value:** `Marketing` (hoặc `Marketing`, `Finance`, `IT` tùy theo cấu trúc của bạn)
        * **Thẻ 2 (Môi trường triển khai):**
            * **Key:** `Environment`
            * **Value:** `Development` (hoặc `Production`, `Staging`, `Test`)
        * **Thẻ 3 (Trung tâm chi phí nội bộ - Tùy chọn nhưng khuyến khích):**
            * **Key:** `CostCenter`
            * **Value:** `CC001` (hoặc mã trung tâm chi phí cụ thể của tổ chức bạn)
        * **Thẻ 4 (Chủ sở hữu hoặc người chịu trách nhiệm chính - Tùy chọn):**
            * **Key:** `Owner`
            * **Value:** `ThanhTung` (hoặc tên người chịu trách nhiệm)
    * Để thêm mỗi thẻ, bạn sẽ nhập Key và Value vào các ô trống, sau đó click vào nút **`Add tag`** hoặc tương tự để thêm hàng mới cho thẻ tiếp theo.
    ![Ảnh 3.2.3.2: Bảng "Add additional tags" với 4 thẻ đã được thêm vào và "Resource types" là "Instances"](/workshop-cost-allocation/images/anh-3/anh-3.2.3.2.png)

    * **Giải thích "Resource types":** Trong giao diện này, bạn sẽ thấy cột "Resource types" bên cạnh mỗi thẻ với giá trị mặc định là "Instances". Điều này chỉ đơn thuần là một chỉ báo rằng các thẻ này sẽ được áp dụng cho loại tài nguyên là EC2 Instance mà bạn đang tạo. Bạn không cần phải thay đổi hay điều chỉnh nó ở đây.
