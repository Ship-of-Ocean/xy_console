# xy_console

- zh_CN [简体中文](readme/README_zh_CN.md)
- zh_TW [繁体中文](readme/README_zh_TW.md)
- en [English](readme/README_en.md)

# Description
Easy Python console tool wrappers

## Install
```

git clone https://github.com/yuyangit/xy_console.git
cd xy_console
python setup.py install

Or

pip install git+https://github.com/yuyangit/xy_console.git --user

```


## Start


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
