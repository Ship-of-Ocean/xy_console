# xy_console

- zh_CN [简体中文](readme/README_zh_CN.md)
- zh_TW [繁体中文](readme/README_zh_TW.md)
- en [English](readme/README_en.md)

如果小伙伴们觉得这些工具还不错的话，能否请咱喝一杯咖啡呢
![微信](readme/WeChat.jpg)
![支付宝](readme/Alipay.jpg)
# 说明
简单Python控制台输入输出工具封装.

## 安装
```

pip install xy_console

```


## 开始


```

from xy_console.utils import *

# 普通打印
printt("hello world")

# 打印成功
print_s("hello world")

# 打印执行
print_exe("hello world")

# 打印警告(warning)
print_w("hello world")

# 打印运行(running)
print_r("hello world")

# 打印运行(error)
print_e("hello world")


```
