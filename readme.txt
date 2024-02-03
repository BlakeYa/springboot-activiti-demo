

项目包含技术点
1、spring boot 2.1.6 整合activiti6.0
2、整合在线流程设计器activiti modoler
3、全局异常处理
4、page-helper分页
5、lombook
6、整合mybatis
7、mybatis generator自动生成代码插件
8、日志使用logback
9、整合swagger

注意：
1. 数据库mysql5.7
2. 连续配置要把useSSL=false 改成false，默认好像也是true，搞了好长时间。恶心的很。
3. datasource.properties 中的driver可以至直接制定maven仓库中的jar包。