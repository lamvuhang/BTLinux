## Tạo 3 user(user-1, user-2, user-3), 2 group(groupA, groupB)

### Create user:
sudo useradd -m -c 'User1' user-1
sudo passwd user-1

sudo useradd -m -c 'User2' user-2
sudo passwd user-2

sudo useradd -m -c 'User3' user-3
sudo passwd user-3

![alt](http://image/create_user.png)

### Create group:
sudo groupadd GroupA
sudo groupadd GroupB

![alt](http://image/create_group.png)
