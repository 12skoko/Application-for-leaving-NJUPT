# Application-for-leaving-NJUPT
南邮自动出校申请脚本

传入一个info字典调用application函数即可使用
```python
info = {
    'account': '',  # 智慧校园账号
    'password': '',  # 智慧校园密码
    'lxdh': '',  # 电话
    'cxsy': '',  # 申请事由
    'jjlxr': '',  # 紧急联系人
    'jjlxrdh': ''  # 紧急联系电话
}

application(info)
```
