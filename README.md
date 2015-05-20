# NewWorld-For-DirectAdmin-Login-Page
登录后退出 返回页

```html
<input type="hidden" value="http://www.elinkhost.com" name="LOGOUT_URL"/>
```
修改为您的网址

 #### 登陆界面安装 ####
 
 ```sh
cd /usr/local/directadmin/data/templates #进入主题所在目录
wget http://www.elinkhost.com/download/Login-Page-2014-4-9.tar.gz #下载Login Page主题模版压缩包
tar xvzf Login-Page-2014-4-9.tar.gz #解压缩
chown -R diradmin:diradmin * #设置主题所有权
rm -f Login-Page-2014-4-9.tar.gz #删除主题模版压缩包
 ```
