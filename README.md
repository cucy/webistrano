ruby version 1.8.7
```
如有必要,安装此版本,即ruby-1.8.7-p352.tar.gz: ruby 1.8.7 (2011-06-30 patchlevel 352) [x86_64-linux]

gem版本使用1.3.7


rails等已集成做vendor目录内,rails version为2.3.5
gems 需要rack=1.0.1, mysql
gem install rack -v=1.0.1
gem install mysql
直接ruby scripts/server运行即
```

```
$ mkdir -p ~/.rvm/user/
$ echo "ruby_url=https://cache.ruby-china.org/pub/ruby" > ~/.rvm/user/db
$ gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
$ \curl -sSL https://get.rvm.io | bash -s stable
$ source ~/.bashrc
$ source ~/.bash_profile

$ rvm install 1.8.7-p352 --disable-binary
```



https://ruby-china.org/wiki/rvm-guide


https://github.com/cucy/webistrano


db 解压执行sql

rvm install rubygems 1.3.7 --force



gem list

*** LOCAL GEMS ***

bundler-unload (1.0.2)
executable-hooks (1.4.2)
gem-wrappers (1.3.2)
iconv (1.0.5)
mysql (2.9.1)
rack (1.0.1)
rake (10.1.1)
rubygems-bundler (1.4.4)
rvm (1.11.3.9)






## 必须按照1

wget https://ftp.gnu.org/pub/gnu/libiconv/libiconv-1.15.tar.gz

libiconv.so.2: cannot open shared object解决方法 2011-09-07 17:11:48
1）如果/usr/local/lib/libiconv.so.2不存在：
需要安装lib相关的源码包，

tar zxvf libiconv-1.13.tar.gz  -C ../software
cd  ./software/libiconv-1.13/
./configure --prefix=/usr/local
make
make install
然后作软连接：
ln -s /usr/local/lib/libiconv.so.2 /usr/lib/libiconv.so.2
再执行一下ldconfig" B&


2）如果/usr/local/lib/libiconv.so.2存在
给libiconv.so.2做个软件链接
ln -s /usr/local/lib/libiconv.so.2 /usr/lib/libiconv.so.2
再执行一下ldconfig" B& M9 ?/ N4 ~. K% A0 W- @
' x/ P  M9 W9 d% l
OK




# 修改admin密码
6e53fb4e26ca4d2278bc4c3355930cf377ef136e
59b3d6f734b09554aeb3e9969bc2340a633fd6b0


# 运行
ruby script/server  -p 13000 -e production

# 包

└──┤ gem list

```
*** LOCAL GEMS ***

bundler-unload (1.0.2)
executable-hooks (1.4.2)
gem-wrappers (1.3.2)
iconv (1.0.5)
mysql (2.9.1)
rack (1.0.1)
rake (10.1.1)
rubygems-bundler (1.4.4)
rvm (1.11.3.9)
```
