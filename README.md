# 功能概述及仿真结果
data_in为随机生成的32位数据输入，模块通过last_in判断packet的大小并将packet的大小传给输出功能。
data_insert为插入的数据，data_insert插入到每个packet的第一拍data里，具体由keep_insert控制。
输出部分读取当前传输packet的大小依次将data输出，data_out当第一拍last_in为高电平时开始输出。

![image](https://user-images.githubusercontent.com/127192970/223397470-a8258876-d39a-4e1c-8429-d08110abb738.png)
![image](https://user-images.githubusercontent.com/127192970/223397629-d1ec41db-8550-428a-a854-8bfaef9b4dfc.png)
