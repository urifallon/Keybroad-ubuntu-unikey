# Keybroad-ubuntu-unikey
Hướng Dẫn Cài Đặt Unikey Trên Ubuntu

## Cập nhật Ubuntu
```
sudo apt-get update && upgrade
```
![Icon](./icon/icon-warning.png) <span style="color: #CECC8C; font-weight: bold;">Bạn cần nhập mật khẩu khi sử dụng câu lệnh ở chế độ root (sudo)</span>


## Cài đặt ibus-unikey
### 1. Sử dụng câu lệnh sau để cài đặt ibus-unikey
```
sudo apt-get install ibus-unikey
```
### 2. Kiểm tra ibus-unikey đã được cài đặt thành công
```
ibus version
```
### 3. Cài đặt thành công

![Alt text](./img/ibus-check.png)

### 4. Khởi động lại máy
```
sudo reboot
```
![Icon](./icon/icon-warning.png) <span style="color: #CECC8C; font-weight: bold;">Câu lệnh này sẽ khởi động lại máy, hãy lưu các dữ liệu quan trọng trước khi thực hiện !!!</span>

## Cài đặt Unikey
### 1. Kiểm tra và chọn Unikey

Setting &#8594; Keyboard &#8594; Input Source &#8594; ⋮ &#8594; Other &#8594; Vietnamese (unikey) &#8594; Add

![Alt text](./img/setUnikey.png)
![Alt text](./img/setUnikey1.png)
![Alt text](./img/setUnikey2.png)

### 2. Cấu hình Ibus

Language Support &#8594; Keyboard input method system &#8594; Ibus &#8594; Close 

![Alt text](./img/setIbus.png)
![Alt text](./img/setIbus1.png)
![Alt text](./img/setIbus2.png)

---
![Icon](./icon/icon-check.png) <span style="color: green; font-weight: bold;"> Bạn đã cài đặt thành công Unikey !</span>