# -Qbot
qq机器人学习过程
由于smartqq协议的消失，很多人也都没怎么去玩qqbot了。之后也算是自己上课闲的无聊，想去找一种办法接着玩下去。就去网上了解了一下。
针对windows操作系统：
	直接下载酷q机器人，再进行操作就好。
	但是问题就来了，你打开软件的时候会弹出（windows script control 缺少报错）
这个问题就来了。
我在网上搜索了很久，得到的答案就是，这是是操作系统内部的问题，只能靠重装系统或者安装游戏库运行插件（这个玩过单机的都知道，但是我也尝试过，并没有什么用处）那么问题就来了，重装系统吗？？感觉不行，毕竟电脑上还有各种数据。
那就不弄了吗？
当然不是，对于这种情况用虚拟机就可以解决
我选择的是安装一个windowsXp的系统（安装时镜像文件要好好选，不然装不上）
对于镜像真滴是要选一下，不然不是装不上就是一堆病毒（虽然没啥影响就是了）。
下面列举几个资源：
1.虚拟机 Invalid system disk 错误解决方法
	https://blog.csdn.net/baishuiniyaonulia/article/details/78413099
2.VM虚拟机装Windows XP系统（建议看完，蛮多要注意的点）
https://blog.csdn.net/zz56z56/article/details/80221467
虚拟机安装好了，我们要怎么实现它与主机的文件交换呢？
	对于这种情况我们可以通过开启共享文件夹来实现主机和虚拟机的文件交换.


当然部署在自己的电脑上始终有些不方便，那我现在就来介绍一下如何搭建在自己的vps（针对linux/mac操作系统）上。
	关于vps的配置要求及购买的话可以参考一下这个链接：
http://www.vpsjxw.com/vps_use/kuq_python_demo/
在vps上搭建就需要使用docker
1.	什么是docker？
30分钟快速入门Docker教程
	https://yq.aliyun.com/articles/697444?spm=a2c4e.11155472.0.0.3fbe7a95UKQPw7
2.	安装docker（这种东西最好还是去官网下载）
https://www.docker.com/get-started
3.	在Linux通过docker安装酷Q
https://www.cnblogs.com/tielemao/p/8462263.html

以上就是我这几天的学习历程.
