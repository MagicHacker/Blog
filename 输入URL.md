# 输入URL发生了什么

1、解析URL，分析URL的协议和请求资源路径是否合法之类的。

2、判断是否命中浏览器缓存。如果命中就直接取缓存的内容。

3、通过DNS域名解析服务获取实际的IP地址。

4、通过三次握手建立TCP链接。

5、发起HTTP请求获取资源。

6、服务器响应请求并返回结果。

7、四次挥手关闭TCP连接。

8、浏览器解析HTML，开始渲染。

9、构建DOM树。

10、构建CSS规则树。

11、构建渲染树，通过将DOM树和CSS规则树结合，构建出渲染树。

12、浏览器完成渲染。