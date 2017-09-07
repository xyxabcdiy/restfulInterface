# 目录
- [目录](#目录)
- [/management/system/password](#managementsystempassword)
    - [POST - 管理员登录](#post---管理员登录)
        - [可选参数形式](#可选参数形式)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)

# /management/system/password
## POST - 管理员登录
### 可选参数形式
type = root | fakeuser | fake

#### 上传数据
| 字段     | 类型   | 示例          | 说明             |
| -------- | ------ | ------------- | ---------------- |
| phone    | String | "12122342343" | 用户手机号       |
| password | String | "FASDFSF"     | 用户密码         |

#### 返回数据
| 字段    | 类型   | 示例 | 说明       |
| ------- | ------ | ---- | ---------- |
| errcode | Number | 0    | 操作错误码 |
