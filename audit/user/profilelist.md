# 目录
- [目录](#%E7%9B%AE%E5%BD%95)
- [/placeholder](#placeholder)
    - [GET - 得到多个用户的profile](#get---%E5%BE%97%E5%88%B0%E5%A4%9A%E4%B8%AA%E7%94%A8%E6%88%B7%E7%9A%84profile)
        - [可选参数形式](#%E5%8F%AF%E9%80%89%E5%8F%82%E6%95%B0%E5%BD%A2%E5%BC%8F)
            - [上传数据](#%E4%B8%8A%E4%BC%A0%E6%95%B0%E6%8D%AE)
            - [返回数据](#%E8%BF%94%E5%9B%9E%E6%95%B0%E6%8D%AE)

# /placeholder
## GET - 得到多个用户的profile
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
| user    | [UserProfile](../../type/user-profile.md)   | [{...}] | 用户资料   |

