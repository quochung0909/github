# github
Các lệnh github

1. Tải git
https://git-for-windows.GitHub.io/

2. Kiểm tra cài đặt thành công
git --version

3. Thiết lập username và email cho git
git config --global user.name "Your Name"
git config --global user.email "your_email@example.com"

4. Lấy repository về máy 
git clone https://github.com/quochung0909/github.git

5. Update code lên trên thùng chứa
cd /dự án
git status // Kiểm tra trạng thái đang ở working coppy hat staging area
git add "tên file" hoặc "." nếu nhiều file
git status // nếu thấy xanh là ở staging area rồi 
git commit -m "comment" 
git status // Nếu trắng không có gì thì đã ở Local Repository rồi, sẵn sáng up lên cloud
git push origin "tên nhánh" // mặc định tên nhánh là main

