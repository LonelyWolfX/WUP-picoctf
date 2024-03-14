chúng ta check file với lệnh file mobpsycho.apk
nhận được thông báo đây là file zip -> tiến hành giải nén
![image](https://github.com/PhanTrung2012/WUP-picoctf/assets/121162586/d6be880c-8804-4848-81f9-b5ab06ae6756)
vào thư mục chứa file và mở file psycho được giải nén
![image](https://github.com/PhanTrung2012/WUP-picoctf/assets/121162586/d06a34a1-9057-40f5-a860-49ae308d9b74)
mở bằng notepad và nps đơn giản chỉ hiện rất nhiều chữ
CTRL + F và tìm chữ flag
![image](https://github.com/PhanTrung2012/WUP-picoctf/assets/121162586/6f9b83dd-4f04-493b-85c4-e028e7a1e6de)
đã có đường dẫn là res/color/flag.txt
mở theo đường dẫn và lấy flag
ở đây có đoạn mã: 7069636f4354467b6178386d433052553676655f4e5838356c346178386d436c5f35326135653264657d
decode từ hexadecimal qua text và có ngay flag: picoCTF{ax8mC0RU6ve_NX85l4ax8mCl_52a5e2de}
