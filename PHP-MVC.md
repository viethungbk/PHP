Học PHP

# 1. Project số 2

Lập trình back-end cho website quản lý nhân sự.

- Các chức năng cần xây dựng:
  - Chức năng thêm mới, sửa, xóa nhân sự
- Các chức năng mới sẽ học:
  - Sử dụng Jquery Ajax load nội dung ngay lập tức khi thêm.
  - Làm chức năng view phân trang
  - Sử dụng nhiều chức năng trên cùng một view
  - Sử dụng nhiều action trên cùng một model và controller.

## 1. Chức năng

- Có một công ty chuyên ship hàng trong Hà Nội
- Có rất nhiều người đăng ký làm Shipper
- Cách tính tiền: mỗi lần chuyển là 30k
- Yêu cầu của website: 
  - Thêm nhân viên gồm: 
    - Tên
    - Tuối
    - Địa chỉ
    - Avatar ảnh (upload)
    - Facebook
    - Điện thoại
    - Số lượng đơn đã hoàn thành
    - Số lượng đơn hàng đã hoàn thành
  - Sửa thông tin của một nhân viên
  - Xóa thông tin của một nhân viên
- Setup cơ bản: 
  - Tạo dữ liệu
  - Chỉnh file autoload.php: $autoload['libraries'] = array('database');  => cho phép lấy đường dẫn tuyệt đối và lấy ra dữ liệu
  - Chinh file database trong folder config
  - Chỉnh file config trong folder config: nhập đường dẫn tuyệt đối của web vào.

## 2. Chức năng

- Bước 1:
  - Tạo view cho phép thêm dữ liệu
  - Kết nối với một hàm trong model, insert vào dữ liệu
  - Điều hướng với controller

## 3. Phần front-end

- Hiển thị danh sách các nhân viên: avatar, tên, sdt...
- 