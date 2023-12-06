# delete linux

1.进入磁盘管理系统，删除分给linux的那个盘区

2.以管理员权限的打开windows终端（命令提示符）

3.输入`diskpart`

4.输入`list disk`

5.输入`select disk <磁盘的数字>`

6.输入`list partition`

7.输入`select partition <系统分区对应的数字>`

8.输入`assign letter=x`               //给路径命名，便于后续查找

9.输入`exit`

10.输入`x:`

11.输入`dir`

12.输入`cd efi`

13.输入`rd <linux名字> /S`            //`S`要大写

## 注：所有的<>不用实际打出



