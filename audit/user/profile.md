# 目录
- [目录](#%E7%9B%AE%E5%BD%95)
- [/placeholder](#placeholder)
    - [GET - 得到用户profile](#get---%E5%BE%97%E5%88%B0%E7%94%A8%E6%88%B7profile)
        - [参数形式](#%E5%8F%82%E6%95%B0%E5%BD%A2%E5%BC%8F)
        - [上传数据](#%E4%B8%8A%E4%BC%A0%E6%95%B0%E6%8D%AE)
        - [返回数据](#%E8%BF%94%E5%9B%9E%E6%95%B0%E6%8D%AE)
            - [User](#user)
    - [POST - 新建一个用户](#post---%E6%96%B0%E5%BB%BA%E4%B8%80%E4%B8%AA%E7%94%A8%E6%88%B7)
        - [参数形式](#%E5%8F%82%E6%95%B0%E5%BD%A2%E5%BC%8F)
        - [上传数据](#%E4%B8%8A%E4%BC%A0%E6%95%B0%E6%8D%AE)
        - [返回数据](#%E8%BF%94%E5%9B%9E%E6%95%B0%E6%8D%AE)

# /placeholder
## GET - 得到用户profile
### 参数形式
+ id = UUID

### 上传数据
无

### 返回数据
| 字段    | 类型   | 示例  | 说明       |
| ------- | ------ | ----- | ---------- |
| errcode | Number | 0     | 操作错误码 |
| user    | User   | {...} | 用户资料   |

#### User
| 字段   | 类型   | 示例                | 说明     |
| ------ | ------ | ------------------- | -------- |
| status | String | "active"            | 用户状态 |
| name   | String | "raregrass"         | 用户名称 |
| age    | Number | 18                  | 用户年龄  |
| icon   | String | "http://icon.com"   | 用户头像 |
| email  | String | raregrass@gmail.com | 用户邮箱 |

## POST - 新建一个用户
### 参数形式
无

### 上传数据
| 字段     | 类型   | 示例                | 说明     |
| -------- | ------ | ------------------- | -------- |
| name     | String | "234234234"         | 用户名   |
| password | String | "FASDFSF"           | 用户密码 |
| status   | String | "active"            | 用户状态 |
| name     | String | "raregrass"         | 用户名称 |
| age      | Number | 18                  | 用户年龄  |
| icon     | String | "http://icon.com"   | 用户头像 |
| email    | String | raregrass@gmail.com | 用户邮箱 |

### 返回数据
| 字段    | 类型   | 示例 | 说明       |
| ------- | ------ | ---- | ---------- |
| errcode | Number | 0    | 操作错误码 |
