 ![image](https://github.com/haicuan139/appcheck/blob/master/%E6%9C%AA%E6%A0%87%E9%A2%98-1.png)
# ----------------------------------------------

# What is an API notification?
- 当服务器检测到您有下架的应用时，我们的服务器会主请求用您配置的URL
- 服务器请求您的URL时会携带以下架应用的数据

- When the server detects that you have an application that has been removed, our server will request the URL you configured.
- The server will carry the data of the following applications when requesting your URL
for example:http://wwww.youhost.com/api?appid=xxxx&appname=xxxx&sid=xxxx

# what is "sid"?
当你在添加应用程序时可以指定一个特殊的参数，你可以使用这个参数来索引你自己的数据
When you add an application you can specify a special parameter that you can use to index your own data.

