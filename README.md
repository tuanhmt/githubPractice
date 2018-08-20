# Bài tập tương tác với Github
1. Luôn nhớ config **user.name** và **user.email** trước khi commit bất cứ thay đổi nào ở local, nó cũng sẽ được lưu trên remote
2. Sau khi **clone** Repo này về máy, dùng câu lệnh **`git branch -a`** để xem danh sách các nhánh ở local và trên remote. Bạn sẽ thấy trên remote có nhánh tên của bạn có dạng như sau **`remotes/origin/[your_name]`**
3. Mặc định khi clone thì git chỉ tạo ra 1 nhánh duy nhất ở local là **Master**, muốn tạo và chuyển sang làm việc ở nhánh của bạn thì chúng ta không sử dụng câu lênh **`git branch ..`** như thông thuờng mà dùng câu lệnh **`git checkout [your_name]`**. Git sẽ tự động tạo ra một nhánh tên **`[your_name]`** ở local tương ứng với nhánh đó ở remote. Dùng **`git branch -a`** để kiểm tra lại.
4. Khi đã active nhánh của bạn rồi thì hay làm các công việc sau:
    1. Tạo một tập tin tên là **`[your_name].txt`** với nội dung là **"Nhánh của [your_name]"**
    2. Tiến hành commit trên nhánh local của bạn
    3. Push thay đổi từ nhánh local lên nhánh remote tương ứng **`git push origin [your_name]`**
