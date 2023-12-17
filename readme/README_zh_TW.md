# xy_console

- zh_CN [简体中文](readme/README_zh_CN.md)
- zh_TW [繁体中文](readme/README_zh_TW.md)
- en [English](readme/README_en.md)

# 說明
簡單Python控制台輸入輸出工具封裝

## 安裝
```

git clone https://github.com/yuyangit/xy_console.git
cd xy_console
python setup.py install

或者

pip install git+https://github.com/yuyangit/xy_console.git --user

```


## 開始


```

from xy_console.utils import *

# 普通列印
printt("hello world")

# 成功列印
print_s("hello world")

# 执行列印
print_exe("hello world")

# 警告(warning)列印
print_w("hello world")

# 运行(running)列印
print_r("hello world")

# 运行(error)列印
print_e("hello world")


```
