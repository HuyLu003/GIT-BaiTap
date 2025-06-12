# GIT-BaiTap
# GIT là gì ? 
- Git là hệ thống quản lý phiên bản phân tán 
- Theo dõi lịch sử thay đổi của dự án ( mã code, ...)
- Quản lý nhiều nhánh phát triển song song
-  Cho phép nhiều người cùng làm việc trên 1 dự án mà không bị xung đột ( conflict )
# Các khái niệm cơ bản trong GIT
## Repository
- Kho chứa mã nguồn, có thể là local hoặc remote (server)
## Commit
- Ghi lại trạng thái của 1 mã nguồn ( sự kiện ) tại 1 thời điểm nhất định
## Branch
- Nhánh phát triển riêng biệt
## Merge
- Gồp nội dung của 1 branch vào 1 nhánh khác
## Clone
- Tải repo từ server về máy
## Pull
- Lấy code mới nhất từ nhánh trên  server về local
## Push
- Đẩy code commit từ local lên server

    #  MỘT SỐ CÂU LỆNH GIT CƠ BẢN
- git init : Khai báo 1 dự án bắt đầu sử dụng git
- git status : Kiểm tra trạng thái thay đổi của các file trong dự án
- git add file_name : Xác nhận (thêm) file thay đổi vào repo của local
- git add . : Xác nhận (thêm) tất cả các file thay đổi vào repo local ( sẵn sàng cho commit )
- git commit -m "Your comment" : Đẩy các file thay đổi vào store local sẵn sàng cho push code lên server và đồng thời thêm comment
- git push origin your_branch : Đẩy code từ local vào nhánh your_branch trên server
- git checkout -b branch_name : Tạo 1 nhánh mới có tên là branch_name đồng thời di chuyển sang nhánh đó