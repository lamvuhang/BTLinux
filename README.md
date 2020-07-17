# Bài 1: config local user.name và user.email của mình

git config  user.name "lamvuhang"
 
git config  user.email "hanglam.24hdev@gmail.com"
 
![alt](./image/config.png)
 
# Bài 2: Tạo một file README.md, commit và push trên master 
 
## kiểm tra các branch:
 
git branch
 
## checkout về branch master:
 
git checkout master
 
## add file 
 
git add .
 
## commit file:
 
git commit -m"create readme.md"

## push file:

git push origin master

![alt](./image/tao_readme_tren_master.png)
 
# Bài 3: Tạo một branch mới với name “demo” và sau đó đổi tên thành “develop”
 
## Tạo branch mới vơi tên "demo" và push
 
git checkout -b demo 
 
git push origin demo
 
![alt](./image/tao_demo.png)
 
## Đổi tên "demo" thành "develop"
 
git branch -m develop

git push origin :demo develop

git push origin -u develop
 
![alt](./image/rename_develop.png)
 
# Bài 4: Trên nhánh “develop”, tạo môt file demo.log, index.html, detail.html. Làm thế nào để git không tracking những file *.log. Sau đó tạo một commit.
 
## Tạo file demo.log, index.html, detail.html trên nhánh "develop"

![alt](./image/file_tren_develop.png)
 
## Tạo file .gitignore
 
touch .gitignore 

![alt](./image/tao_gitignore.png)
 
## Thêm nội dung vào file .gitignore
 
![alt](./image/ndgitignore.png)
  
## Tạo commit
  
git add .
   
git commit -m"bt4"
  
![alt](./image/commitbt4.png)
 
# Bài 5: Thay đổi nội dung file index,html, detail.html và save. Sau đó revert lại nội dung commit gần nhất của 1 file index.html. Rồi tạo một commit mới, push.
 
## Thay đổi nội dung file index,html, detail.html và save.
 
![alt](./image/change_index_detail.png)
  
## Revert lại nội dung commit gần nhất của 1 file index.html.
  
git chechout -- index.html
  
![alt](./image/checkout_filename.png)
   
![alt](./image/index_after_revert.png)
 
## Tạo một commit mới, push 
 
 ![alt](./image/push_bt5.png)

# BÀi 6: Từ master tạo một branch testing. Sau đó merge develop vào testing branch. Tạo một pull request merge testing vào master.

## Tạo branch testing từ master 

git checkout master 

git checkout -b testing

 ![alt](./image/tao_testing.png)
 
 ## Merge develop vào testing branch
 
 git merge develop

  ![alt](./image/merge_develop.png)





















