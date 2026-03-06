# Sports Shop E-Commerce System

## 1. Giới thiệu dự án

**Sports Shop E-Commerce System** là hệ thống bán đồ thể thao trực tuyến, được xây dựng nhằm hỗ trợ người dùng tìm kiếm, lựa chọn và mua các sản phẩm thể thao một cách nhanh chóng, thuận tiện và hiện đại.

Hệ thống mô phỏng mô hình của một nền tảng thương mại điện tử hoàn chỉnh, bao gồm:

- Quản lý người dùng
- Quản lý sản phẩm thể thao
- Danh mục sản phẩm
- Giỏ hàng
- Đặt hàng
- Thanh toán online
- Chat hỗ trợ khách hàng
- Theo dõi đơn hàng
- Quản trị hệ thống

Dự án được chia thành 2 phần chính:

- **Backend:** PHP  
- **Frontend:** Java  

Mục tiêu của dự án là xây dựng một hệ thống bán hàng thực tế, rõ ràng về nghiệp vụ, dễ mở rộng, dễ bảo trì, và giúp người đọc chỉ cần xem README là có thể hiểu hệ thống làm được những gì.

---

## 2. Mục tiêu dự án

Dự án được xây dựng nhằm đáp ứng các mục tiêu sau:

- Xây dựng hệ thống bán đồ thể thao trực tuyến theo mô hình thương mại điện tử
- Giúp người dùng dễ dàng tìm kiếm và mua sản phẩm
- Hỗ trợ thanh toán online nhanh chóng và an toàn
- Tạo môi trường tương tác giữa khách hàng và cửa hàng thông qua chức năng chat
- Hỗ trợ quản trị viên quản lý toàn bộ sản phẩm, đơn hàng, khách hàng và doanh thu
- Tạo nền tảng có thể phát triển thêm app mobile hoặc tích hợp các dịch vụ bên thứ ba trong tương lai

---

## 3. Mô tả bài toán

Shop thể thao cần một hệ thống để bán các mặt hàng như:

- Giày thể thao
- Áo thể thao
- Quần thể thao
- Vợt cầu lông / tennis
- Bóng đá / bóng rổ
- Phụ kiện thể thao
- Túi đựng đồ thể thao
- Dụng cụ tập gym / yoga

Thay vì quản lý thủ công, hệ thống này giúp:

- Hiển thị sản phẩm chuyên nghiệp
- Quản lý tồn kho
- Hỗ trợ người dùng mua hàng online
- Tự động hóa quy trình đặt hàng
- Theo dõi trạng thái đơn hàng
- Tích hợp thanh toán online
- Giao tiếp với khách hàng qua chức năng chat

---

## 4. Công nghệ sử dụng

### Backend
- **PHP**
- Xây dựng RESTful API để cung cấp dữ liệu cho Frontend
- Xử lý nghiệp vụ:
  - đăng ký / đăng nhập
  - quản lý sản phẩm
  - giỏ hàng
  - đơn hàng
  - thanh toán
  - chat
  - quản trị hệ thống

### Frontend
- **Java**
- Xây dựng giao diện người dùng
- Hiển thị dữ liệu sản phẩm, danh mục, giỏ hàng, đơn hàng
- Gửi request đến Backend API
- Xử lý tương tác người dùng

### Cơ sở dữ liệu
- MySQL / MariaDB *(hoặc có thể thay bằng hệ quản trị CSDL phù hợp với project)*

---

## 5. Đối tượng sử dụng

Hệ thống phục vụ 2 nhóm người dùng chính:

### 5.1. Khách hàng
Người dùng truy cập hệ thống để:

- Đăng ký tài khoản
- Đăng nhập
- Xem sản phẩm
- Tìm kiếm sản phẩm
- Lọc theo danh mục
- Thêm vào giỏ hàng
- Đặt hàng
- Thanh toán online
- Chat với shop
- Xem lịch sử mua hàng
- Theo dõi trạng thái đơn hàng
- Cập nhật thông tin cá nhân

### 5.2. Quản trị viên
Admin sử dụng hệ thống để:

- Quản lý danh mục sản phẩm
- Quản lý sản phẩm
- Quản lý kho hàng / số lượng tồn
- Quản lý đơn hàng
- Quản lý khách hàng
- Quản lý thanh toán
- Quản lý nội dung chat hỗ trợ
- Xem báo cáo doanh thu
- Theo dõi hoạt động hệ thống

---

## 6. Chức năng chính của hệ thống

## 6.1. Chức năng tài khoản người dùng

Hệ thống hỗ trợ đầy đủ chức năng tài khoản:

- Đăng ký tài khoản mới
- Đăng nhập
- Đăng xuất
- Quên mật khẩu
- Đổi mật khẩu
- Cập nhật thông tin cá nhân
- Cập nhật địa chỉ nhận hàng
- Phân quyền người dùng:
  - Khách hàng
  - Quản trị viên

### Ý nghĩa
Chức năng này giúp hệ thống nhận diện người dùng, lưu thông tin mua hàng, hỗ trợ thanh toán và quản lý đơn hàng cá nhân.

---

## 6.2. Chức năng quản lý sản phẩm

Hệ thống cho phép hiển thị và quản lý các sản phẩm thể thao như:

- Tên sản phẩm
- Mã sản phẩm
- Hình ảnh sản phẩm
- Mô tả chi tiết
- Giá bán
- Giá khuyến mãi
- Số lượng tồn kho
- Thương hiệu
- Kích thước / size
- Màu sắc
- Trạng thái còn hàng / hết hàng

### Các chức năng liên quan
- Xem danh sách sản phẩm
- Xem chi tiết sản phẩm
- Tìm kiếm sản phẩm theo tên
- Lọc sản phẩm theo:
  - danh mục
  - giá
  - thương hiệu
  - kích cỡ
  - loại thể thao

### Ý nghĩa
Đây là chức năng trung tâm của hệ thống, giúp người dùng dễ dàng tiếp cận thông tin sản phẩm trước khi mua hàng.

---

## 6.3. Chức năng danh mục sản phẩm

Sản phẩm được chia theo nhóm để dễ quản lý và tìm kiếm, ví dụ:

- Giày thể thao
- Áo thể thao
- Quần thể thao
- Dụng cụ gym
- Phụ kiện
- Bóng thể thao
- Vợt thể thao

### Chức năng
- Hiển thị danh mục
- Xem sản phẩm theo từng danh mục
- Admin thêm / sửa / xóa danh mục

### Ý nghĩa
Giúp tổ chức hệ thống sản phẩm khoa học, dễ tìm kiếm và dễ mở rộng.

---

## 6.4. Chức năng giỏ hàng

Người dùng có thể thao tác với giỏ hàng như một website thương mại điện tử thực tế:

- Thêm sản phẩm vào giỏ hàng
- Cập nhật số lượng sản phẩm
- Xóa sản phẩm khỏi giỏ hàng
- Xem tổng tiền tạm tính
- Tính phí vận chuyển dự kiến
- Áp dụng mã giảm giá *(nếu có)*

### Ý nghĩa
Giỏ hàng đóng vai trò trung gian trước khi người dùng xác nhận đặt hàng.

---

## 6.5. Chức năng đặt hàng

Sau khi chọn xong sản phẩm, người dùng có thể đặt hàng với các bước:

- Kiểm tra lại giỏ hàng
- Nhập thông tin nhận hàng
- Chọn phương thức giao hàng
- Chọn phương thức thanh toán
- Xác nhận đặt hàng

### Trạng thái đơn hàng có thể gồm
- Chờ xác nhận
- Đã xác nhận
- Đang chuẩn bị hàng
- Đang giao hàng
- Giao thành công
- Đã hủy

### Ý nghĩa
Chức năng này giúp hệ thống quản lý quy trình mua hàng từ lúc khách đặt đến khi hoàn tất giao hàng.

---

## 6.6. Chức năng thanh toán online

Hệ thống hỗ trợ thanh toán trực tuyến để tăng tính tiện lợi cho người dùng.

### Có thể hỗ trợ các hình thức
- Thanh toán khi nhận hàng (COD)
- Chuyển khoản ngân hàng
- Thanh toán qua cổng thanh toán online
- Ví điện tử *(nếu tích hợp)*

### Quy trình thanh toán
- Người dùng chọn hình thức thanh toán
- Hệ thống tạo đơn hàng
- Chuyển tới bước xác nhận thanh toán
- Ghi nhận kết quả thanh toán
- Cập nhật trạng thái đơn hàng

### Ý nghĩa
Giúp hệ thống hoạt động giống một nền tảng thương mại điện tử thực tế, hỗ trợ thanh toán nhanh và chuyên nghiệp hơn.

---

## 6.7. Chức năng chat hỗ trợ khách hàng

Hệ thống có chức năng chat giữa khách hàng và shop.

### Mục đích
- Tư vấn sản phẩm
- Hỗ trợ chọn size
- Giải đáp về giá, khuyến mãi
- Kiểm tra tình trạng đơn hàng
- Hỗ trợ sau bán hàng

### Chức năng chat có thể gồm
- Gửi tin nhắn giữa khách hàng và shop
- Hiển thị danh sách hội thoại
- Đọc / chưa đọc
- Gửi ảnh minh họa *(nếu mở rộng)*
- Lưu lịch sử chat

### Ý nghĩa
Tăng khả năng tương tác, nâng cao trải nghiệm người dùng và hỗ trợ chốt đơn hiệu quả hơn.

---

## 6.8. Chức năng đánh giá và nhận xét sản phẩm

Người dùng sau khi mua hàng có thể:

- Đánh giá số sao cho sản phẩm
- Viết nhận xét
- Gửi phản hồi về chất lượng sản phẩm

### Ý nghĩa
Giúp tăng độ tin cậy cho sản phẩm và hỗ trợ người mua sau có thêm thông tin tham khảo.

---

## 6.9. Chức năng yêu thích / wishlist

Người dùng có thể:

- Lưu sản phẩm yêu thích
- Xem lại danh sách sản phẩm đã lưu
- Thêm sản phẩm vào giỏ hàng từ wishlist

### Ý nghĩa
Hỗ trợ người dùng ghi nhớ sản phẩm quan tâm và quay lại mua sau.

---

## 6.10. Chức năng quản lý đơn hàng cá nhân

Khách hàng có thể:

- Xem danh sách đơn hàng đã đặt
- Xem chi tiết từng đơn hàng
- Theo dõi trạng thái giao hàng
- Hủy đơn hàng khi đơn chưa xử lý
- Xem lịch sử thanh toán

### Ý nghĩa
Giúp người dùng chủ động quản lý việc mua hàng của mình.

---

## 6.11. Chức năng quản trị hệ thống

Admin có toàn quyền quản lý hệ thống.

### Quản lý sản phẩm
- Thêm sản phẩm mới
- Chỉnh sửa sản phẩm
- Xóa sản phẩm
- Cập nhật tồn kho
- Quản lý hình ảnh sản phẩm

### Quản lý danh mục
- Thêm danh mục
- Sửa danh mục
- Xóa danh mục

### Quản lý đơn hàng
- Xem toàn bộ đơn hàng
- Cập nhật trạng thái đơn hàng
- Xác nhận đơn
- Hủy đơn
- Kiểm tra thanh toán

### Quản lý người dùng
- Xem danh sách khách hàng
- Khóa / mở khóa tài khoản
- Theo dõi lịch sử mua hàng

### Quản lý chat
- Trả lời khách hàng
- Theo dõi lịch sử hỗ trợ
- Quản lý các cuộc hội thoại

### Báo cáo thống kê
- Tổng số đơn hàng
- Doanh thu theo ngày / tháng / năm
- Sản phẩm bán chạy
- Khách hàng mua nhiều nhất

### Ý nghĩa
Đây là phần giúp shop vận hành hệ thống một cách đầy đủ, chuyên nghiệp và có tổ chức.

---

## 7. Nghiệp vụ chính của hệ thống

Một luồng hoạt động cơ bản của hệ thống như sau:

### Bước 1: Người dùng truy cập hệ thống
- Xem trang chủ
- Xem danh mục nổi bật
- Xem sản phẩm mới / sản phẩm bán chạy

### Bước 2: Tìm kiếm sản phẩm
- Tìm theo tên
- Lọc theo danh mục
- Lọc theo mức giá
- Lọc theo thương hiệu

### Bước 3: Xem chi tiết sản phẩm
- Hình ảnh
- Mô tả
- Giá
- Size
- Màu sắc
- Số lượng còn lại
- Đánh giá từ người dùng khác

### Bước 4: Thêm vào giỏ hàng
- Chọn size / màu / số lượng
- Thêm sản phẩm vào giỏ

### Bước 5: Đặt hàng
- Kiểm tra giỏ hàng
- Nhập địa chỉ nhận hàng
- Chọn phương thức thanh toán
- Xác nhận đơn

### Bước 6: Thanh toán
- Thanh toán online hoặc COD
- Hệ thống ghi nhận trạng thái thanh toán

### Bước 7: Theo dõi đơn hàng
- Người dùng xem trạng thái đơn
- Admin cập nhật tiến trình xử lý đơn hàng

### Bước 8: Hỗ trợ sau mua
- Chat với shop
- Đánh giá sản phẩm
- Phản hồi dịch vụ

---

## 8. Các module chính trong hệ thống

Dự án có thể chia thành các module sau:

- **Authentication Module**
  - đăng ký, đăng nhập, phân quyền

- **User Module**
  - hồ sơ cá nhân, địa chỉ, đổi mật khẩu

- **Category Module**
  - quản lý danh mục sản phẩm

- **Product Module**
  - quản lý sản phẩm, thông tin chi tiết, tồn kho

- **Cart Module**
  - giỏ hàng, cập nhật số lượng, xóa sản phẩm

- **Order Module**
  - tạo đơn hàng, quản lý trạng thái đơn hàng

- **Payment Module**
  - xử lý thanh toán online, lưu thông tin giao dịch

- **Chat Module**
  - nhắn tin hỗ trợ giữa khách hàng và shop

- **Review Module**
  - đánh giá, bình luận sản phẩm

- **Admin Module**
  - quản lý toàn bộ hệ thống

- **Report Module**
  - thống kê doanh thu, đơn hàng, sản phẩm bán chạy

---

## 9. Lợi ích của hệ thống

Dự án mang lại nhiều lợi ích thực tế như:

- Giúp cửa hàng thể thao quản lý bán hàng hiệu quả hơn
- Giúp khách hàng mua hàng online tiện lợi
- Tăng khả năng tiếp cận khách hàng
- Tăng doanh thu nhờ hỗ trợ thanh toán online và chat tư vấn
- Tăng trải nghiệm người dùng với giao diện trực quan, quy trình mua hàng rõ ràng
- Dễ mở rộng thêm khuyến mãi, voucher, livestream bán hàng, app mobile...

---

## 10. Hướng phát triển trong tương lai

Trong tương lai, hệ thống có thể mở rộng thêm:

- Tích hợp chatbot tự động
- Gợi ý sản phẩm thông minh
- Tích hợp nhiều cổng thanh toán hơn
- Quản lý voucher / mã giảm giá
- Theo dõi vận chuyển theo thời gian thực
- Thông báo đẩy
- Phiên bản mobile app
- Hệ thống chăm sóc khách hàng nâng cao
- Báo cáo doanh thu trực quan bằng biểu đồ

---

## 11. Kết luận

**Sports Shop E-Commerce System** là một dự án mô phỏng hệ thống bán đồ thể thao trực tuyến đầy đủ nghiệp vụ của một nền tảng thương mại điện tử hiện đại.

Dự án không chỉ hỗ trợ các chức năng cơ bản như xem sản phẩm, mua hàng, đặt hàng, mà còn mở rộng sang các chức năng quan trọng như:

- thanh toán online
- chat hỗ trợ khách hàng
- quản lý đơn hàng
- đánh giá sản phẩm
- quản trị hệ thống
- báo cáo doanh thu

Với kiến trúc tách biệt giữa **Backend PHP** và **Frontend Java**, hệ thống có thể dễ dàng phát triển, bảo trì và mở rộng trong tương lai.

---

## 12. Từ khóa chính của dự án

- Sports Shop
- E-Commerce
- PHP Backend
- Java Frontend
- Online Payment
- Shopping Cart
- Order Management
- Product Management
- Customer Chat
- Admin Dashboard
