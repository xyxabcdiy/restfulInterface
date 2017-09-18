# 目录
- [目录](#目录)
- [/password](#password)
    - [POST - 更新管理员密码](#post---更新管理员密码)
        - [可选参数形式](#可选参数形式)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)

# /password
## POST - 更新管理员密码
### 可选参数形式

#### 上传数据
| 字段     | 类型   | 示例          | 说明             |
| -------- | ------ | ------------- | ---------------- |
| phone    | String | "12122342343" | 管理员手机号       |
| password | String | "FASDFSF"     | 管理员密码         |
| vcode    | Number | 23232         | 管理员收到的验证码 |

#### 返回数据
| 字段    | 类型   | 示例 | 说明       |
| ------- | ------ | ---- | ---------- |
| errcode | Number | 0    | 操作错误码 |