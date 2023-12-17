# xy_console
# 说明
简单控制台输入输出工具封装.

## 安装
```

git clone https://github.com/yuyangit/xy_console.git
cd xy_console
python setup.py install

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
