# Tên Dự Án : Robot vận hành và giám sát kho xưởng

## Mô Tả

Đề tài nghiên cưu tạo ra một mô hình robot 4 bánh điều khiển bởi sóng RF và jostick cùng với cánh tay robot được điều khiển qua áp từ local ip , có camera để quan sát hình ảnh được gửi về qua điện thoại. Cánh tay robot có thể tự học lệnh và lưu trữ dữ liệu trong Ram của vi điều khiển ESP32, khi được yêu cầu cánh tay sẽ tự động thao tác lại những gì đã ghi nhớ. Kết hợp quản lí thông số môi trường qua Blynk IOT và hệ thống pin năng lượng mặt trời tự điều hướng giúp tối ưu năng lượng ánh sáng bảo vệ môi trường . 

## Chức Năng

 **Nhiệm Vụ:** 
- Tìm hiểu vể Esp32 camera cùng arduino Uno R3 và các động cơ DC, module sóng RF,cảm biến ánh sáng và servo mg90s. 
- Viết giải thuật cho cánh tay robot tự học
- Viết giải thuật cho hệ thống pin năng lượng tự điều hướng
- Tìn hiểu source code giúp tạo ra một giao diện điều khiển có stream hình ảnh từ camera về điện thoại cũng như giúp cánh tay robot tự hoc lệnh
- In 3d cánh tay robot và khung pin năng lượng điều hướng 
- Lắp ráp linh kiện và tiến hành thử nghiệm sửa lỗi 

## Mô tả hoạt động

**Hoạt động** Robot sẽ được điều khiển qua joystick vs module sóng RF di chuyển đến địa điểm yêu cầu, từ hình ảnh của camera người dùng có thể thấy vật thể và điều chỉnh cánh tayrobot gắp vật thể đấy di chuyển đến nơi khác. Nêu vật thể ở có định 1 chỗ thì người dùng sẽ yêu cầu robot tự học lệnh qua nút nhấn ở trên giao diện điều khiển và sau đó yêu cầu thực hiện lại, robot sẽ thực hiện cho đến khi được yêu cầu dùng hoặc đến khi hết pin. Pin năng lượng mặt trời 2 trục sẽ giúp nhận ánh sáng từ nhiều phía. Trước xe có gắn 1 esp32 camera giúp quét mã QR code được gắn trên mặt hàng, đọc mã qr code đó và gửi thông tin về ứng dụng telegram của người dùng. Ngoài ra hệ thông cugn4 sẽ giám sát nhiệt độ và độ âm môi trường thể hiên qua Blynk IOT có cảnh báo khi thông số vượt ngưỡng.   

## Liên Hệ

- Tên: [ĐỖ THÀNH PHÁT]
- Email: dothanhphat01@gmail.com
