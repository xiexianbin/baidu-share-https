# 百度分享不支持Https的解决方案  #

### 使用方法： ###
将static文件夹放在网站的根目录下，或CDN中。并将对应的百度分享代码中，

    static\api\js\share.js
    domain: {staticUrl: "http://bdimg.share.baidu.com/"}
    修改为：
    domain: {staticUrl: "/"}
    或：
    domain: {staticUrl: "https://cn-cdn.xiexianbin.cn/"}
    

