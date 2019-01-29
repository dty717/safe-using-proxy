# safe-using-proxy

首先,在此之前做如下声明,现在网络上提供的的许多面免费的科学上网,也就是翻墙,都会提供许多翻墙之后需要浏览的网站,请不要相信,
以我个人为例,我也是曾经是"免费科学上网"使用的受害者,这些网址的错误观点只会让我对当前社会产生的反感不信任,最终摧毁了我的
政治思想,以至于我到现在不敢谈及政治,因为我现在都不相信自己的政治观点.

话题有些沉重,忘了吧,言归正传.

## 总体思路
如何实现翻墙,首先你需要一个可以浏览国外网站的正常使用的服务器A,其次你能和服务器A正常连接,然后你就通过服务器A正常访问外国
网站

## 第一步:购买租用的服务器

在这里我推荐使用<a href="https://bwh8.net/">搬瓦工</a>,点开网站,选择相应的服务

![alt text](https://github.com/dty717/safe-using-proxy/blob/master/picture/2019-01-29_08-27-11.gif)
![alt text](https://github.com/dty717/safe-using-proxy/blob/master/picture/2019-01-29_08-41-21.gif)

记住到以上这一步在选择Billing Cycle时,有半年和一年的选项,价格是不一样的,但是平均价格差不多

接下来是付款环节,填写相关的用户信息,在Payment Method选项时选择Alipay,在同意用户协议后点击complete order按钮
![alt text](https://github.com/dty717/safe-using-proxy/blob/master/picture/2019-01-29_08-54-41.gif)
![alt text](https://github.com/dty717/safe-using-proxy/blob/master/picture/chrome_2019-01-29_09-01-17.png)
之后点Pay,接下来就是正常的支付宝操作

在成功之后,点击services下的my services
![alt text](https://github.com/dty717/safe-using-proxy/blob/master/picture/2019-01-29_09-11-51.gif)
点击KiwiVM Control Panel按钮
![alt text](https://github.com/dty717/safe-using-proxy/blob/master/picture/chrome_2019-01-29_09-14-01.png)
在新的界面下,你将获得两个重要的信息,一个是IP address,一个是SSH Port
![alt text](https://github.com/dty717/safe-using-proxy/blob/master/picture/2019-01-29_09-20-05.gif)
接下来更重要的是生成root的密码,点击Root password modification后,点击Generate and set new root password,获得root密码
记住root密码,只会显示一次,之后只能重新生成
![alt text](https://github.com/dty717/safe-using-proxy/blob/master/picture/2019-01-29_09-23-11.gif)

## 第二步:连接配置服务器

首先你需要有一个连接的工具,推荐使用<a href="https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html">putty</a>,点开https://www.chiark.greenend.org.uk/~sgtatham/putty/latest.html,
进行下载安装.

