#  Giới thiệu
![](./image/robot_visai.jpg)

Robot bánh xe vi sai là loại robot bánh xe được cấu trúc:
- Hai bánh điều khiển ở hai bên được gắn động cơ, bình thường hai bánh xe quay cùng tốc độ, muốn điều khiển robot sang phải thì tốc độ bánh xe bên phải phải nhỏ hơn bên trái, và ngược lại
- Một hoặc hai bánh xe cân bằng

Project này tạo robot bánh xe vi sai, mô phỏng trên gazebo và điều khiển chuyển động thông qua bàn phím.

# Mô phỏng robot tự hành
- Hiển thị trên Gazebo:
```bash
$ source devel/setup.bash
$ roslaunch robot_banhxe_visai robot_banhxe_visai_gazebo.launch
```
- Mở cửa sổ rviz: mở một **Terminal** mới
```bash
rosrun rviz rviz
```

- Điều khiển bằng amcl (http://wiki.ros.org/amcl): mở một **Terminal** mới
```bash
$ roslaunch robot_banhxe_visai amcl.launch
```
- Đặt điểm đích để robot tự hành tới bằng công cụ "2D Nav Goal".
