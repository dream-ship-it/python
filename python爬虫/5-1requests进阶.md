## requests进阶概述

- 在之前的爬虫中其实已经使用过headers了. header为HTTP协议中的请求头.一般存放一些和请求内容无关的数据.有时也会存放一些安 全验证信息.比如常见的User-Agent, token, cookie等.
- 通过requests发送的请求，可以将请求头信息放在headers中，页可以单独进行存放，最终由requests自动帮我们拼接成完整的请求头

## 内容
1. 模拟浏览器登录 -> 处理cookie
2. 防盗链处理 -> 抓取一些数据
3. 代理 -> 防止IP被封










