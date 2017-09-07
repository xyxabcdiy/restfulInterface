# 目录
- [目录](#目录)
- [/user/profile](#userprofile)
    - [GET - 获取user profile列表](#get---获取user-profile列表)
        - [可选参数形式](#可选参数形式)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)
        - [可选参数形式](#可选参数形式)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)
    - [PUT - 更新用户资料](#put---更新用户资料)
        - [可选参数形式](#可选参数形式)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)

# /user/profile
## GET - 获取user profile列表
### 可选参数形式
+ sort= rank | date
+ start = 0
+ count = 10
+ [ tag = nodejs & tag = xmt & tag = battle ]
+ [ label = official & good & lala ]

#### 上传数据
无

#### 返回数据
| 字段    | 类型             | 示例    | 说明          |
| ------- | ---------------- | ------- | ------------- |
| errcode | Number           | 0       | 操作错误码    |
| user    | Array<UserBrief> | [{...}] | 返回的dig列表 |

### 可选参数形式
+ id = uuid

#### 上传数据
无

#### 返回数据
| 字段    | 类型   | 示例  | 说明       |
| ------- | ------ | ----- | ---------- |
| errcode | Number | 0     | 操作错误码 |
| user    | User   | {...} | 返回的dig  |

## PUT - 更新用户资料
### 可选参数形式
+ id = UUID

#### 上传数据
| 字段       | 类型   | 示例        | 说明     |
| ---------- | ------ | ----------- | -------- |
| lastname?  | String | "raregrass" | 用户姓氏 |
| firstname? | String | "raregrass" | 用户名字 |
| birthday?  | String | "2017-1-1"  | 用户生日 |

#### 返回数据
| 字段    | 类型   | 示例 | 说明       |
| ------- | ------ | ---- | ---------- |
| errcode | Number | 0    | 操作错误码 |
