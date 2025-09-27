# Simple Auth

## Test với Postman
Run file app.js: node app.js
Ảnh request register:  
Tiến hành đăng ký tài khoản với đường dẫn local/register trong POSTMAN với phương thức POST

![Register với Postman](./public/img/1.png)
Check in database xem có đã được lưu chưa
![user đã đăng kí](./public/img/2.png)
tiến hành login và xem kết quả, thành công sẽ hiển thị thông báo "Login successful!"
![user đăng nhập](./public/img/3.png)
Check in database xem đã được lưu session chưa
![check data](./public/img/4.png)
go to profile: dùng phương thức GET để xem thông tin, thành công sẽ trả về thông báo tên người dùng
![profile](./public/img/5.png)
go to logout and check cookie is deleted in database: kết quả sau khi logout thì DB cũng xóa luôn cookie
![logout](./public/img/6.png)
![logout](./public/img/7.png)

![cookie](./public/img/9.png)
