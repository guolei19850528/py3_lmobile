# py3_lmobile

The Python3 lmobile Library Developed By Guolei

# Installation

```shell
pip install py3_lmobile
```

# Documentation

## [Docment](https://www.lmobile.cn/ApiPages/index.html)

# Example

## SMS

```python
from py3_lmobile.sms import Sms

sms = Sms(
    account_id="",
    password="",
    product_id=""
)
state = sms.send_sms(phone_nos="", content="【签名】测试通知短信")
if state:
    print("send sms success")
else:
    print("send sms fail")
```
