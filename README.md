# -
DatenLord面试项目题-IC前端设计
data_in为随机生成的32位数据输入，模块通过last_in判断packet的大小并将packet的大小传给输出功能。
data_insert为插入的数据，data_insert插入到每个packet的第一拍data里，具体由keep_insert控制。
输出部分读取当前传输packet的大小依次将data输出，data_out当第一拍last_in为高电平时开始输出。

![image](https://user-images.githubusercontent.com/127192970/223397203-14283039-5291-46a8-ae28-eab99579a419.png)
