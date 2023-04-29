# 注意事项
需要您的电脑安装Python和两个库

`pip install loguru `

`pip install requests `

签到完成，他不会领取，记得自己去手机上领取一下

例如:延期卡 观影卡 会员卡

# pip 报错解决办法

打开环境变量 选择path 新建 找到你的Python安装路径

打开Scripts 文件夹 复制路径 填写路径

`C:\Users\你电脑的用户名\AppData\Local\Programs\Python\Python310\Scripts\`

你如果设置的安装默认路径的话，可以打以下命令

`%USERPROFILE%\AppData\Local\Programs\Python`


# 功能介绍:
目前可以补签(需要你的账户处于登录状态)

实际上网页登录就可以了

# 阿里云盘 获取refresh_token 链接
[跳转链接](https://github.com/fgr178707/aliyunpan/wiki/%E9%98%BF%E9%87%8C%E4%BA%91%E7%9B%98-%E8%8E%B7%E5%8F%96refresh_token-%E9%93%BE%E6%8E%A5)

# 目前已知的bug
是当天签到可能会提 **[None->None]**

它提示这个可能是今天真就没有东西给或者是数据读取错误  不影响今天签到

他虽然提示这个但是 你看前面只要有对勾就表示签到
