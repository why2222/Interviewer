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
