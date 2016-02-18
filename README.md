# zookeeper-web

### 源自淘宝开源

源代码地址  http://code.taobao.org/p/zkweb/wiki/index/

### 解决问题

* 解决必须事先创建表问题(H2数据库)
* 解决spring多个版本依赖引起jar包问突问题
* 解决查询请求返回406问题，spring配置使用json返回体问题

## 使用方法

下载源代码，执行'mvn clean package -DskipTests'，把war包放到webapps目录就行了
