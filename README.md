CẬP NHẬP DL 19/4/23
Bài 1 :
![image](https://user-images.githubusercontent.com/125638408/232957638-b245b4d1-9908-4435-8b92-837c66e27629.png)
nhìn vào source code t dễ dàng thấy dòng  code có chứa flag :strcpy(src, "flag-PS_The_bird_bites");
v là ta đã lấy đc flag bài 1 :D
Bài 2 :
Với bài 2 này flag cũng hiện rõ trên source code
![image](https://user-images.githubusercontent.com/125638408/232958303-e64639cb-773c-490a-8113-3c7a32f68fc2.png)
đây là flag ( dòng được bôi đen trên ida ) 
![image](https://user-images.githubusercontent.com/125638408/232958648-92fae972-7df1-40ce-8c14-9a2695f25e05.png)
Bài 3 : 
Bài 3 này trên source code là số ta cần phải định dạng lại để lấy đc flag, theo như tôi tìm hiểu gần đây thì đây chính là mã ascii viết ở dạng hệ thập phân:D
![image](https://user-images.githubusercontent.com/125638408/232959443-fa08b448-f2d6-493c-a479-de8800287044.png)
Chúng ta có 2 cách để giải quyết bài này :
1.dò từng số với bảng mã ascii
2. chuyển số trên ida về dạng kí tự (chả)
Mình là ng tiêu dùng thông minh nên chọn cách 2 :D
![image](https://user-images.githubusercontent.com/125638408/232959991-29628285-6be5-475a-9f19-54abdb99f3d2.png)
vậy là sẽ ra flag : flag-most_muggles_aren\t_exactly_accustomed_to_seeing_a_flying_car
Done!e
