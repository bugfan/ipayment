## 免签约个人微信/支付宝收款码支付系统

## 系统包含的组件
- 支付管理
  - Golang后端程序
  - Vue前端程序
  - Mysql
- Android apk安装包

## 说明

#### 特点
- 不用开公司
- 不用接商户复杂的支付api
- 钱直接到自己账户
- 没有传统第三方商户签约抽成/手续费
- 灵活，适合个人小团队
- 对接超简单
- 可自己私有化部署

#### 付款流程
1. 付款用户打开在支付管理里面预先配置好的付款信息页面，然后扫码支付。
2. Android app启动后会监听支付消息，如果收到付款，会通知支付管理系统。
3. 支付管理收到回调消息会做一系列校验操作与通知操作。
4. 最终付款用户的付款页面会自动跳转提示成功。

#### 支付管理
```
已经打包成了docker镜像和二进制程序(支持linux/win/mac)
用于记录管理订单，个人支付码，支付成功回调参数，登录日志，Android APK回调日志，以及管理账号设置
```

#### Android程序
```
已经打包成apk了，用于发送回调信息以及显示支付日志

```

## 视频演示地址
https://mp.weixin.qq.com/s?__biz=MzU5NTQ2NTg0Mw==&mid=2247484178&idx=1&sn=a68d2c931edbe0bb9f4494c146e54c52&chksm=fe70c00ec90749181789abc683ce6f4b0d58eab8707495ebeb31d061a7ea690736fd9bc2cec6#rd

## 如何使用？
由于精力有限，目前需要打赏后才能使用！ 如需使用，关注下方公众号，加我vx:fanwxm，打赏点就能使用了😊😊😊 （毕竟创作不易啊）

## 关注我公众号获取"联系方式"和"交流群"
![image](https://github.com/bugfan/ipayment/blob/main/img/gzh.jpg)


## 一些使用截图
![image](https://github.com/bugfan/ipayment/blob/main/img/1.png)
![image](https://github.com/bugfan/ipayment/blob/main/img/2.jpeg)
![image](https://github.com/bugfan/ipayment/blob/main/img/3.jpeg)
![image](https://github.com/bugfan/ipayment/blob/main/img/4.jpeg)
![image](https://github.com/bugfan/ipayment/blob/main/img/5.jpeg)
![image](https://github.com/bugfan/ipayment/blob/main/img/6.jpeg)
![image](https://github.com/bugfan/ipayment/blob/main/img/7.jpeg)
![image](https://github.com/bugfan/ipayment/blob/main/img/8.jpeg)
![image](https://github.com/bugfan/ipayment/blob/main/img/9.jpeg)
![image](https://github.com/bugfan/ipayment/blob/main/img/apk.JPG)
