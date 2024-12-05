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
from py3_lmobile.sms import SMS

sms = SMS(
    account_id="<AccountId>",
    password="<Password>",
    product_id="<ProductId>"
)
state, _ = sms.send_sms(phone_nos="<phone_no1,phone_no2>", content="【签名】短信内容")
if state:
    print("successful")
```
