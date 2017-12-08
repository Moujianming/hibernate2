# hibernate注解开发
*[各个类分析](https://github.com/Moujianming/hibernate2/tree/master/src/com/pojo)
一共是3个类,分别是User,Product,Category分别有自己的id等属性字段
*各个类之间的关系
User-Product是多对多的关系,一个用户可以购买多种商品,多种商品可以被1个用户购买
Product-Category是一对多的关系,一个Product只能是属于某一种分类
Category-Product是多对一的关系,一个分类里面可以有多个Product
*[hibernate配置文件](https://github.com/Moujianming/hibernate2/blob/master/src/hibernate.cfg.xml)
主要是保存连接数据库的相关信息和连接属性的类等信息

除此之外,注解开发可以自动的生成相应的数据表
