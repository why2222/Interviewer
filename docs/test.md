* **数据库**
  * 数据库主键、外键

  * 索引有哪些，如何建立索引

  * 给定商品和商品价格，找出价格最低的五个商品
  ```sql
  select good,price from table order by price asc limit 5
  # 价格最高的5个
  select good,price from table order by price desc limit 5
  ```
* **网络**
  * 输入url之后，页面发生了什么
  * url的组成
    ```
    <scheme>://<user>:<password>@<host>:<port>/<path>:<params>?<query>#<frag>
    ```
  * [状态码](https://www.jianshu.com/p/f9c6ed6fa35e)
    * 1XX 信息提示
    * 2XX 请求成功
    * 3XX 重定向
    * 4XX 客户端错误
    * 5XX 服务器错误
  * [GET和POST](https://www.oschina.net/news/77354/http-get-post-different)
  
  |分类|GET|POST|
  |:---:|:---:|:---:|
  |回退/刷新|无害|数据会被重新提交|
  |Book|可收藏为书签|不可收藏为书签|
  |Cache|能被缓存|不能被缓存|
  |编码类型|application/x-www-form-urlencoded|application/x-www-form-urlencoded 或 multipart/form-data为二进制数据使用多重编码|
  |历史|参数表留在浏览器历史记录中|参数不会保留在浏览器历史记录中|
  |数据类型|ACII|没有限制，允许二进制|
  |安全性|与 POST 相比，GET 的安全性较差，因为所发送的数据是 URL 的一部分。在发送密码或其他敏感信息时绝不要使用 GET ！|POST 比 GET 更安全，因为参数不会被保存在浏览器历史或 web 服务器日志中。|
  |可见性|	数据在 URL 中对所有人都是可见的|数据不会显示在 URL 中|
  
  * **!** HTTP的底层是TCP/IP。所以GET和POST的底层也是TCP/IP，也就是说，GET/POST都是TCP链接。GET和POST能做的事情是一样一样的。你要给GET加上request body，给POST带上url参数，技术上是完全行的通的。 

* **测试**
  * 对登录界面进行测试

  * 对测试的理解

  * [微信发红包如何需要测试哪些方面](https://blog.csdn.net/yimixgg/article/details/94741910)

    * 功能测试
    * 兼容性测试
    * 性能测试
    * UI测试&易用性测试
    * 中断测试
    * 网络测试
  * [用过哪些抓包工具](https://zhuanlan.zhihu.com/p/44912855)
    * fiddler
    * wireshark
* **linux**
  * 命令
    * 修改用户权限 chown
    * 查看当前端口的进程状态 netstat
    * 查看当前路径 pwd
    * 查看文档的后100行 tail -n 100 filename 
