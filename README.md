# BigData-ProJect
  大数据专题大作业
**环境搭建**

windows系统:
搭建中间有很多坑，且行且注意。

配置要求：要求配置neo4j数据库及相应的python依赖包。neo4j数据库用户名密码记住，并修改相应文件。

安装neo4j，neo4j 依赖java jdk 1.8版本以上：

java jdk安装方法可参考：windows系统下安装JDK8，下载地址：https://download.oracle.com/otn-pub/java/jdk/8u201-b09/42970487e3af4f5aa5bca3f542482c60/jdk-8u201-windows-x64.exe

安装neo4j可参考博文：windows安装neo4j，下载地址：https://go.neo4j.com/download-thanks.html?edition=community&release=3.4.1&flavour=winzip

安装python可参考：Windows环境下安装python2.7

根据neo4j 安装时的端口、账户、密码配置设置设置项目配置文件：answer_search.py &  build_medicalgraph.py (github下载项目时根据个人需要也可使用git)

数据导入：python build_medicalgraph.py，导入的数据较多，估计需要几个小时。

python build_medicalgraph.py导入数据之前，需要在该文件main函数中加入：

 build_medicalgraph.py

启动问答：python chat_graph.py


Mac系统
mac本身自带python、java jdk环境，可直接安装neo4j图数据库，项目运行步骤与windows基本一样。
