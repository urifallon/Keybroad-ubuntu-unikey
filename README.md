# Keybroad-ubuntu-unikey
Hướng Dẫn Cài Đặt Unikey Trên Ubuntu

## Cap nhat ubuntu
```
sudo apt-get update && upgrade
```
![Icon](./icon/icon-warning.png) <span style="color: #CECC8C; font-weight: bold;">ban can nhap mat khau o che do root (sudo)</span>


## Cai dat ibus-unikey
### 1. su dung cau lenh phia duoi de cai dat wibus-unikey
```
sudo apt-get install ibus-unikey
```
### 2. kiem tra ibus-unikey da duoc cai dat thanh cong
```
ibus version
```
### 3. hinh anh khi cai dat thanh cong

![Alt text](./img/ibus-check.png)

### 4. khoi dong lai may
```
sudo reboot
```
![Icon](./icon/icon-warning.png) <span style="color: #CECC8C; font-weight: bold;">cau lenh nay se khoi dong lai may, hay luu cac thong tin quang trong truoc khi thuc hien</span>

## Cai dat unikey
### 1. kiem tra unikey va chon

Setting &#8594; Keyboard &#8594; Input Source &#8594; ⋮ &#8594; Other &#8594; Vietnamese (unikey) &#8594; Add

![Alt text](./img/setUnikey.png)
![Alt text](./img/setUnikey1.png)
![Alt text](./img/setUnikey2.png)

### 2. cau hinh ibus

Language Support &#8594; Keyboard input method system -> Ibus

![Alt text](./img/ibus-check.png)