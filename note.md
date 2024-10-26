# Term
Repository (Repo): thư mục dự án
Branch
Conflict
Local
Remote
gitignore


# Commands
- git init
- git status: cho thấy trạng thái hiện tại
- git add: chuẩn bị thời điểm lưu lại dự án
- git add .: để chuẩn bị lưu lại tất cả file
- git reset : để bỏ chuẩn bị lưu các file
- git commit -m 'ghi chú': để chính thức lưu file
- git log
- git log --oneline: xem các lần commit trước gọn hơn
- git checkout {id}: để xem log có id đó
- git branch: xem nhánh hiện tại
- git checkout -b {branch name} : tạo ra một branch mới
- git merge {branch name}: gộp nhánh
- git branch -d {branch name} : xóa nhánh
- git push: đẩy local repo của mình lên trên remote repo (github)
- (terminal) git clone {url} : đưa repo về thư mục hiện tại trên máy
- (terminal) cd {thư mục}: chuyển đến thư mục cần mở
- (terminal) code . :để chạy code trên vscode
- git push -u origin {branch name}: đẩy branch vừa tạo lên github
, lần sau không cần dùng origin chỉ cần push bình thường
- git fetch origin: rồi sau đó dùng git checkout -b {branch name} origin/{branch name}: để chuyển sang nhánh đã tạo sẵn trên github
- sau khi đã pull request trên github
-> ta chuyển lại về nhánh master mặc định
-> git pull để lưu thay đổi