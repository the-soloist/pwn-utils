# pwnutils

封装一些常用的功能 \_(:з」∠)\_

## ENV

```
Linux or MacOS
python 3.10.x
```

## INSTALL

```sh
# 安装依赖
pip3 install -r requirements.txt
pip3 install pwntools==4.3.1 --user
pip3 install pybase62 psutil prettytable termcolor tabulate pycryptodome websocket-client

git clone https://github.com/thenoviceoof/base92 pkg/base92
git clone https://github.com/stek29/base100 pkg/base100

# 导入模块
PWNUTILS_DIR="/path/to/pwnutils"
git clone https://github.com/the-soloist/pwn-utils $PWNUTILS_DIR
export PYTHONPATH="$PYTHONPATH:$PWNUTILS_DIR"

# 或者 python 中加入
sys.path.append("/path/to/pwnutils")

# 修改环境变量
export PATH="$PATH:/path/to/pwnutils/bin"
```

## USAGE

```python
from pwn import *
from pwnutils import *
```

# REFERENCE

1. https://github.com/ray-cp/pwn_debug
2. https://github.com/pullp/pwn_framework
3. ···
