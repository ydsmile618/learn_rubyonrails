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
