## **CLIProxyAPI反代教程，爽用大模型Api**

CLIProxyAPI使用会简单一些，兼容性也更好，主流龙虾都可以使用，教程以Windows为例上手难度较低，反代大模型Api使用

![bdc657db93f2c85a696fcf6b6d540381.png](./_resources/bdc657db93f2c85a696fcf6b6d540381.png)

推荐Windows 服务器部署CLIProxyAPI，24小时不间断调用大模型Api

腾讯云新加坡，硅谷，东京地区价格是199元一年，2核4G30M带宽，60GBSSD盘 1.5T月流量

购买地址：https://curl.qcloud.com/oyWDLkRJ

![fb3690586c0a318c63818db6fda5d765.png](./_resources/fb3690586c0a318c63818db6fda5d765.png)

## **教程**

1.去下载项目，以Windows举例

地址：https://github.com/router-for-me/CLIProxyAPI/releases

![6dc6297428503a0b22d8b9f8bfb14a4c.png](./_resources/6dc6297428503a0b22d8b9f8bfb14a4c.png)

2.复制一份config.example.yaml重命名为config.yaml

![12d85f6090207da0a9d5ec388cd4df7b.png](./_resources/12d85f6090207da0a9d5ec388cd4df7b.png)

3.打开config.yaml，把allow-remote的false改为true，secret-key填入123456

![df9778a9afa5ddf6f69c3dcd242c60c8.png](./_resources/df9778a9afa5ddf6f69c3dcd242c60c8.png)

4.在项目文件夹运行命令

`./cli-proxy-api.exe`

![a06a828ba15e6e994788f010f118a05a.png](./_resources/a06a828ba15e6e994788f010f118a05a.png)

5.浏览器访问，输入密码123456

http://localhost:8317/management.html

![15fbb7f0923e6b34e121ed55895c1e11.png](./_resources/15fbb7f0923e6b34e121ed55895c1e11.png)

6.左侧找到OAuth 登录

![0d875be306f04afcf8aaeea0db816a67.png](./_resources/0d875be306f04afcf8aaeea0db816a67.png)

7.以qwen为例，点击登录后打开链接

![0148002cbe7d845a3a57a783e3ca19d0.png](./_resources/0148002cbe7d845a3a57a783e3ca19d0.png)

8.邮箱注册登录

![686dae8c1cc6b9bfa8d158f87996966c.png](./_resources/686dae8c1cc6b9bfa8d158f87996966c.png)

9.在信息中心，就是可以调用的模型了

![ba5c185d5829fdfffa2ff22913b54858.png](./_resources/ba5c185d5829fdfffa2ff22913b54858.png)

接口：http://localhost:8317/v1

模型：qwen3-coder-plus