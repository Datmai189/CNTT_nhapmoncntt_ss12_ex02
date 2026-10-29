Phần 1 : 
1.Dòng nguy hiểm nhất là dòng 1
08:15 T2	campuspay_beta_users.xlsx	Thành viên A	Editor	Anyone with the link
đây là dòng nguy hiểm vì anyone with the link thì tất cả mọi người có link đều có thể đọc được nội dung trong file
nữa là editor có thể chỉnh sửa đc
2 -Quyền đã bị thay đổi sau 09:30: Chủ sở hữu hoặc một Editor đã thêm email người lạ và quyên editor nhưng sự kiện này chưa được ghi trong bảng log.
  -Người lạ sử dụng được file: File có thể nằm trong một thư mục chia sẻ cho người lạ
  -Tài khoản hoặc bản sao file bị lộ
Phần 2 : 
3. Viết lại 
Tên file     |	Quyền đúng  |	Phạm vi đúng
campuspay_beta_users.xlsx | 	Viewer;  | QA cần thiết mới được Editor	Restricted
campuspay_api_keys.txt |	Viewer |	Restricted 
slide_pitch_v8.pptx |	Commenter |	Restricted 
4. khoá link
Vào Manage access, chuyển Anyone with the link thành Restricted và chọn Remove access với người không còn được phép truy cập
Set Expiration Date dùng khi chỉ muốn cấp quyền tạm thời còn nếu đã xảy ra rò rỉ thì phải thu hồi quyền luôn
