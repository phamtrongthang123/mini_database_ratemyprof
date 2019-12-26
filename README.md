# mini_database_ratemyprof

# Dựng lại databse

Tạo thư mục database bằng `mkdir ./data`

gán mongo database path bằng cách gõ bên dưới
```
sudo mongod --dbpath=./data
```
## Cách 1:
xong gọi `node app.js` để insert bọn data vào , hiện tại có 9 collections (table) tất cả.

Để kiểm tra bằng mongo shell thì tại terminal gõ `mongo`, sau đó `use myproject`, sau đó `show collections`, hiện đủ 9 bảng là ok

## Cách 2: 
sau khi clone về vào cd vào thư mục, gõ lệnh 
```
mongorestore  ./dump/
```
