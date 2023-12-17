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

# Normal Print
printt("hello world")

# Success Print
print_s("hello world")

# Execute Print
print_exe("hello world")

# Warning Print
print_w("hello world")

# Running Print
print_r("hello world")

# Error Print
print_e("hello world")


```
