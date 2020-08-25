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

* **测试**
  * 对登录界面进行测试

  * 对测试的理解

  * 微信发红包如何需要测试哪些方面

    * 功能测试
    * 兼容性测试
    * 性能测试
    * UI测试&易用性测试
    * 中断测试
    * 网络测试
  * 用过哪些抓包工具
    * fiddler
    * wireshark
