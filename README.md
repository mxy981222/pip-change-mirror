# pip-change-mirror
This is a simple note about how to change the download source of pip, since the speed may be very slow. 

```shell
pip install pip -U
pip config set global.index-url https://pypi.tuna.tsinghua.edu.cn/simple
```
