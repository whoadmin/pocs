## 描述
* 基于Pocsuite3框架
* 所有的POC都使用python3从新编写或修改
* 部分POC并未有环境进行测试
* 所有的POC都只写了verify
* POC将会不定期更新
* 主要方便工作中的漏洞验证
* 有任何问题请Issue

## 问题说明
* 部分使用了socket包的POC如果无法验证漏洞是因为python2转python3的编码问题, python3的 socket.send()需要的是byte类型参数

## 使用方法
* 请查看pocsuite3的官方文档 
[https://github.com/knownsec/pocsuite3]

## 更新日志
* 2019/10/25 提交10个POC
* 2019/10/28 提交php-fpm远程代码执行漏洞POC, 漏洞编号CVE-2019-11043
* 2019/11/04 提交Kibana < 6.6.0 Timelion rce漏洞POC
* 2019/11/05 提交Apache Solr <= 8.2.0 rce 漏洞POC
* 2019/11/05 提交Zookeeper未授权访问漏洞POC
* 2019/11/06 提交Zabbix 2.2 < 3.0.3 API JSON-RPC rce漏洞POC
* 2019/11/06 提交Zabbix 2.2 < 3.0.3 jsrpc 参数profileIdx2 insert注入漏洞POC
* 2019/11/06 提交Zabbix <= 4.4 验证绕过漏洞POC
* 2019/11/06 提交Weblogic SSRF漏洞POC
* 2019/11/06 提交Zabbix 2.2 < 3.0.3 latest SQL注入漏洞POC
* 2019/11/07 提交Weblogic T3协议反序列化rce漏洞POC, 漏洞编号CVE-2016-0638
* 2019/11/07 提交Weblogic T3协议反序列化rce漏洞POC, 漏洞编号CVE-2016-3510
* 2019/11/07 提交Weblogic T3协议反序列化rce漏洞POC, 漏洞编号CVE-2017-3248
* 2019/11/08 提交Weblogic wls-wsat协议反序列化rce漏洞POC, 漏洞编号CVE-2017-3506
* 2019/11/08 提交Weblogic T3协议反序列化rce漏洞POC, 漏洞编号CVE-2017-3248
* 2019/11/08 提交Weblogic T3协议反序列化rce漏洞POC, 漏洞编号CVE-2018-2628
* 2019/11/08 提交Weblogic T3协议反序列化rce漏洞POC, 漏洞编号CVE-2018-2893
* 2019/11/08 提交Weblogic 两处任意文件上传漏洞POC, 漏洞编号CVE-2018-2894
* 2019/11/08 提交Weblogic wls-wsat协议反序列化rce漏洞POC, 漏洞编号CVE-2019-2725
* 2019/11/08 提交Weblogic wls-wsat协议反序列化rce漏洞POC, 漏洞编号CVE-2019-2729
* 2019/11/11 提交Java RMI 反序列化漏洞漏洞POC
* 2019/11/13 提交phpmyadmin <= 2.11.9.1 rce漏洞POC, 漏洞编号CVE-2008-4096
* 2019/11/13 提交Jenkins rce漏洞POC, 漏洞编号CVE-2018-1000861
* 2019/11/14 提交Hadoop Yarn Rest API rce漏洞POC
* 2019/11/14 提交Hadoop jstack pstack Servlet rce漏洞POC
* 2019/11/15 提交Apache Flink 任意jar包上传rce漏洞POC
* 2020/6/30  提交Nexus 3 任意修改admin密码越权漏洞POC, 漏洞编号CVE-2020-11444
* 2020/6/30  提交Nexus Manager 3 远程命令执行漏洞POC, 漏洞编号CVE-2020-10204
* 2020/6/30  提交Nexus Manager 3 远程命令执行漏洞POC, 漏洞编号CVE-2020-10199
* 2020/6/30  提交Nexus Manager 3 远程命令执行漏洞POC, 漏洞编号CVE-2019-7238
* 2020/6/30  提交Spring Expression Language SpEL 远程代码漏洞POC, 漏洞编号CVE-2018-1273
* 2020/7/01  提交Apache Struts2 S2-057 远程代码执行漏洞POC, 漏洞编号CVE-2018-11776

## 致谢
* 感谢开放POC的所有大神, 感谢你们的默默奉献, 小弟沾你们的光了
* weblogic系列漏洞改写了 https://github.com/rabbitmask/WeblogicScan