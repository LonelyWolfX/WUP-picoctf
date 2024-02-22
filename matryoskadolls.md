tải ảnh về mở lên để check đúng ảnh hay không
![dolls](https://github.com/LonelyWolfX/WUP-picoctf/assets/121162586/fe394925-eb1d-4ce1-90c5-f88467bbf6ff)
//con búp bê này nguồn gốc từ Nga, có cấu tạo nhiều búp bê nhỏ hơn ở bên trong
binwalk -e để lấy thông tin
![image](https://github.com/LonelyWolfX/WUP-picoctf/assets/121162586/2f7f68c5-3d21-4b83-a3b2-03d72446536e)
ở đây có file đuôi extracted tiến hành cd vào
![image](https://github.com/LonelyWolfX/WUP-picoctf/assets/121162586/0cd656f6-417b-439e-a794-47398ae53bb8)
unzip file zip thì nó thông báo có file 2_c.jpg trong dir base_image
![image](https://github.com/LonelyWolfX/WUP-picoctf/assets/121162586/d051a179-1ab9-4bb2-8758-0331452bea96)
cd vào và giải nén ảnh 
![image](https://github.com/LonelyWolfX/WUP-picoctf/assets/121162586/0e7ea8f0-68a4-4b4a-b7d1-e50b9a6ba5e8)
làm tương tự thế tới khi tìm được file 4_c.jpg
giải nén và có flag 
![image](https://github.com/LonelyWolfX/WUP-picoctf/assets/121162586/f7174832-9370-4c11-9f9d-23c52028dd13)
flag: picoCTF{96fac089316e094d41ea046900197662}
