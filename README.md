# jfinal-oauth2.0-server

- 更新 JF 到 最细的 JF2.1；
- 更新 JF-Ext2到2.0.1；
- 将项目转为 maven 管理；
- 修改了项目结构；

基于[JFinal2.1](https://github.com/JFinal/JFinal)，[JFinal-ext2-v2.0.1](https://github.com/BruceZCQ/JFinal-ext2)
参考[RFC6749](http://www.rfcreader.com/#rfc6749)实现了4.节描述的内容。

实现了OAuth 2.0定义了四种授权方式

- 授权码模式（authorization code）： 先获取下次请求token的code，然后在带着code去请求token；
- 简化模式（implicit）：直接请求token； 
- 密码模式（resource owner password credentials）： 先完成授权，然后再获取token；
- 客户端模式（client credentials）： 类似密码保护模式；
​

demo [http://localhost:8080/jfinal-oauth2.0-server/index.jsp](http://localhost:8080/jfinal-oauth2.0-server/index.jsp)