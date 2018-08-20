# Bài tập tương tác với Github
1. Luôn nhớ config **user.name** và **user.email** trước khi commit bất cứ thay đổi nào ở local, nó cũng sẽ được lưu trên remote
2. Sau khi **clone** Repo này về máy, dùng câu lệnh git branch -a để xem danh sách các nhánh ở local và trên remote. Bạn sẽ thấy trên remote có nhánh tên của bạn có dạng như sau **`remotes/origin/[ten_ban]`**
3. Mặc định khi clone thì git chỉ tạo ra 1 nhánh duy nhất ở local là **Master**, muốn tạo và chuyển sang làm việc ở nhánh của bạn thì chúng ta không sử dụng câu lênh **`git branch ..`** như thông thuờng mà dùng câu lệnh **`git checkout [ten_ban]`**. Git sẽ tự động tạo ra một nhánh tên **`[ten_ban]`** ở local tương ứng với nhánh đó ở remote.
