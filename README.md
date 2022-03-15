# WebView
1.get和post的区别
答案：
(1)GET和POST，两者是HTTP协议中发送请求的方法
(2)GET方法请求一个指定资源的表示形式，使用GET的请求应该只被用于获取数据,POST方法用于将实体提交到指定的资源，通常导致在服务器上的状态变化或副作用
(3)GET在浏览器回退时是无害的，而POST会再次提交请求;GET参数通过URL传递，POST放在Request body中；GET请求在URL中传送的参数是有长度限制的，而POST没有；GET比POST更不安全，因为参数直接暴露在URL上，所以不能用来传递敏感信息；GET请求只能进行url编码，而POST支持多种编码方式；
2.http和https协议
答案：
(1)HTTP协议是超文本传输协议的缩写，英文是Hyper Text Transfer Protocol。它是从WEB服务器传输超文本标记语言(HTML)到本地浏览器的传送协议;设计HTTP最初的目的是为了提供一种发布和接收HTML页面的方法。
(2)http是明文传输的，比如post请求的参数容易被获取，端口号是80，https是在http基础上增加了ssl协议，会建立一个信息安全通道，保证数据的安全，保证网站的真实性，区别在于需要证书;加密传输身份认证的网络协议;端口443
3.cookie和session的区别
答案
(1)作用范围不同，Cookie 保存在客户端（浏览器），Session 保存在服务器端。
(2)有效期不同，Cookie 可设置为长时间保持，比如我们经常使用的默认登录功能，Session 一般失效时间较短，客户端关闭或者 Session 超时都会失效。
(3)隐私策略不同，Cookie 存储在客户端，比较容易遭到不法获取，早期有人将用户的登录名和密码存储在 Cookie 中导致信息被窃取；Session 存储在服务端，安全性相对 Cookie 要好一些。
(3)存储大小不同， 单个 Cookie 保存的数据不能超过 4K，Session 可存储数据远高于 Cookie。
