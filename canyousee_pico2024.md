chúng ta tải file về và tiến hành giải nén
![image](https://github.com/PhanTrung2012/WUP-picoctf/assets/121162586/ecf2b9c7-046c-42af-9803-00ce0ad1270d)
chúng ta có 2 file unknown.zip và ukn_reality.jpg
check qua file và phát hiện ra ukn_reality.jpg là 1 file ảnh
![image](https://github.com/PhanTrung2012/WUP-picoctf/assets/121162586/4778528f-ef6d-40a7-a59f-f167b1fb0ceb)
dùng HxD mở nó lên
đẻ ý file hex dưới cùng có 1 đoạn mã base64
![image](https://github.com/PhanTrung2012/WUP-picoctf/assets/121162586/26378592-1d6a-48e0-b2ea-35ce4aea4b2d)
decode và có flag:picoCTF{ME74D47A_HIDD3N_deca06fb}
