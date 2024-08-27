# hostloc-checkin

Hostloc 签到 并自动推送至Telegram（TG-BOT） 基于Python3

# 新版说明

config.py 需要填写的参数有 username,password,TGBOTAPI,TGID


## 准备工作

SSH，Python3全家桶，Hostloc账号名和密码

## 使用方法

py自己上传到对应目录即可，默认用的/root/

如果是其他目录请自行修改SH的文件内容

## 定时任务

30 1 * * * python3 /root/hostloc.py

[或者把python3的路径也加上]

# 参考资料

https://github.com/BlueSkyXN/Hostloc-Checkin
