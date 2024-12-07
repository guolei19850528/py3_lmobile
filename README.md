# py3_lmobile
The Python3 lmobile Library Developed By Guolei

# Installation
```shell
pip install py3_lmobile
```
# Official Documentation

## [Home](https://www.lmobile.cn/ApiPages/index.html)

# Example
## SMS
```python
from py3_lmobile.sms import Sms

sms = Sms(
    account_id="dljtwy00",
    password="g07KjuLN1",
    product_id=1012808
)
state = sms.send_sms(phone_nos="15210720528,18910415280", content="【金泰物业】测试通知短信")
print(state)
```
