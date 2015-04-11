# learn_rubyonrails
test

2015-4-5 19:00:53
在阿里云（CentOS）上安装Ruby on Rails 时，总是出现以下错误：

<code># sudo gem install rails
ERROR:  Could not find a valid gem 'rails' (>= 0), here is why:
          Unable to download data from https://rubygems.org/ - SSL_connect SYSCALL returned=5 errno=0 state=SSLv3 read server session ticket A (https://rubygems.org/latest_specs.4.8.gz)
ERROR:  Possible alternatives: rails
</code>


让我很是崩溃。刚从CodeCademy那里学到一些RoR的东西，想要自己操作都不能实现。
太过于复杂。

于是在网上搜索解决办法，目前正在尝试：
http://blog.sina.com.cn/s/blog_b043152601018mua.html

2015-4-5 21:44:18：
后续更新：
1， 重装服务器系统为ubuntu，还是不行
2， 最终发现错误在两个地方：一是gem install rails 上， 因为访问外网不畅。最终是采用淘宝的镜像；另一个是install bundle 的问题，也是由于有墙的原因。

遇见此类问题的解决方案可以参考：
https://ruby-china.org/topics/9367

ps.这是一个好的社区网站


<h2> 如何更新Ubuntu上Ruby版本 </h2>
2015-4-6 23:33:36
我现在在学习
http://guides.rubyonrails.org/getting_started.html
这是一个比较好的RoR教程。

可以在云端进行编译
（https://ide.c9.io/nickwangyida/rails-tutorial#openfile-README.md）

我也想在Ubuntu 服务器上进行同步学习。在版本设定时遇到问题：
gem要求ruby 版本大于2.0
于是尝试更新Ubuntu上ruby版本

【方法1】最终尝试的解决办法如下：
http://www.cnblogs.com/neil-yang/p/3266673.html
源代码安装

<h2>国内ubuntu安装Ruby和Rails的最佳教程</h2>
2015年4月7日13:48:44：
【方法1】失败

找到了一个国内ubuntu安装ruby和rails 的最佳教程：
http://www.cnblogs.com/piaolingzxh/p/4217480.html
《ubuntu 14.04中安装 ruby on rails 环境（填坑版） 呕血推荐》

<h2>出现"E: Unable to locate package curl"的解决办法</h2>
http://stackoverflow.com/questions/27273412/cannot-install-packages-inside-docker-ubuntu-image


<h2>放弃其他平台，仅通过Ruby on Rails Tutorial来学习RoR</h2>
2015-4-11 23:10:08

<h3>Ruby on Rails Tutorial推荐的一个类Github网站，放弃使用；一个heroku，部署不成功，放弃使用，以后有经验之后，可以从头学习 </h3>
<h3>学习Ruby on Rails Tutorial 的时候，Chapter4出现问题，修改不成功，只好从一开始进行部署。</h3>
