chạy thử file cat.png thì đúng là có ảnh tổng tài bên cạnh chiếc lap trăm tỏi của anh ấy.
tiếp tục binwalk và strings thì ko có kết quả
![image](https://github.com/LonelyWolfX/WUP-picoctf/assets/121162586/45e0362d-6787-426e-913d-f4cd955996c3)

mở HxD kiểm tra thì có 2 dòng base64: W5M0MpCehiHzreSzNTczkc9d và cGljb0NURnt0aGVfbTN0YWRhdGFfMXNfbW9kaWZpZWR9
![image](https://github.com/LonelyWolfX/WUP-picoctf/assets/121162586/7d2187ca-1973-458b-9e61-b47134cd8707)

![image](https://github.com/LonelyWolfX/WUP-picoctf/assets/121162586/044603f4-ab90-4b83-b777-8ca93f795fe8)

tiến hành decode và có flag picoCTF{the_m3tadata_1s_modified}
