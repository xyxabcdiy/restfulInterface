# 目录
- [目录](#目录)
- [/admin/user/profile](#adminuserprofile)
    - [GET - 得到用户profile](#get---得到用户profile)
        - [可选参数形式](#可选参数形式)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)
        - [可选参数形式](#可选参数形式)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)
    - [POST - 新建一个用户](#post---新建一个用户)
        - [可选参数形式](#可选参数形式)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)
- [User字段](#user字段)

# /admin/user/profile
## GET - 得到用户profile
### 可选参数形式
+ id = UUID

#### 上传数据
无

#### 返回数据
| 字段    | 类型   | 示例  | 说明       |
| ------- | ------ | ----- | ---------- |
| errcode | Number | 0     | 操作错误码 |
| user    | User   | {...} | 用户资料   |

### 可选参数形式
+ sort= rank | date
+ start = 0
+ count = 10
+ [ tag = nodejs & tag = xmt & tag = battle ]
+ [ label = official & good & lala ]

#### 上传数据
无

#### 返回数据
| 字段    | 类型   | 示例    | 说明       |
| ------- | ------ | ------- | ---------- |
| errcode | Number | 0       | 操作错误码 |
| user    | User   | [{...}] | 用户资料   |

## POST - 新建一个用户
### 可选参数形式
无

#### 上传数据
| 字段     | 类型   | 示例        | 说明     |
| -------- | ------ | ----------- | -------- |
| name     | String | "234234234" | 用户名   |
| password | String | "FASDFSF"   | 用户密码 |

#### 返回数据
| 字段    | 类型   | 示例 | 说明       |
| ------- | ------ | ---- | ---------- |
| errcode | Number | 0    | 操作错误码 |

# User字段
| 字段   | 类型   | 示例                | 说明     |
| ------ | ------ | ------------------- | -------- |
| status | String | "active"            | 用户状态 |
| name   | String | "raregrass"         | 用户名称 |
| age    | Number | 18                  | 用户年龄  |
| icon   | String | "http://icon.com    | 用户头像 |
| email  | String | raregrass@gmail.com | 用户邮箱 |
