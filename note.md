# terms
    Repository (Repo) : kho lưu trữ, thư mục
    Branch: cành, nhánh
    Conflict: xung đột
    Local
    Remote
# command
- git init: khởi tạo 1 git repository
- git status: trạng thái của các thay đổi trong repo
- git add: chuẩn bị lưu 1 file trong repo
- git add . : chuẩn bị lưu all file trong repo
- git reset: hoàn lại các tác vụ đã lưu khi gõ git add
- git commit: hoàn chỉnh việc lưu file và đẩy lên github, đại diện cho dự án đang ở đâu và tới chức năng gì
- git log: coi lại các thời điểm đã commit
- git log --oneline
- git checkout <id>: trở lại phiên trước khi commit
- git checkout {branch name}: trả về nhánh làm việc hiện tại (hiện tại có thể là master)
- git branch: show các branch hiện có
- git checkout -b {branch name}: tạo ra 1 branch mới
- git merge {branch name}: hợp branch lại với nhau
- git branch -d {branch name}: xoá 1 branch
- git push: đẩy dự án từ local repo lên github remote

- example:
    git remote add origin https://github.com/thebao2507/First.git 
    git push origin {branch name}


- git push -u origin {branch name}: đấy 1 nhánh branch lên git remote
- lấy 1 nhánh branch có sẵn từ github về:
    + git fetch origin
    + git checkout -b {branch name} origin/{branch name}

- git pull: lấy về các thay đổi trên remote