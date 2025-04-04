Cách gửi lên git từ git bash:

1- Vào thư mục muốn gửi lên->chuột phải->chọn open git bash here

2- gõ git init                                                           
để khởi tạo

3- gõ touch .gitignore
Để tạo mục loại trừ       
(code trong git đấy)

4- gõ git remote add origin https://github.com/bl205vn/TestthuLanbon.git 
(sau origin là đường dẫn đến git cần gửi file lên)

5- gõ git add .                                                          
để thêm toàn bộ file trong thư mục vào chỗ chuẩn gửi lên

6- Gõ git status 
để kiểm tra

7- Gõ git commit -m "Add code nhap trinh game 2d"                        
để bắt đầu tạo gói để gửi lên git. Trong "" là ghi chú (kiểu vậy)

8- git push -u origin master                                             
bắt đầu gửi lên, mục master là tên nhánh   
Nhớ đăng nhập nữa
