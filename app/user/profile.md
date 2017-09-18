# 目录
- [目录](#%E7%9B%AE%E5%BD%95)
- [/user/profile](#userprofile)
    - [GET - 获取user profile信息](#get---%E8%8E%B7%E5%8F%96user-profile%E4%BF%A1%E6%81%AF)
        - [参数形式](#%E5%8F%82%E6%95%B0%E5%BD%A2%E5%BC%8F)
        - [上传数据](#%E4%B8%8A%E4%BC%A0%E6%95%B0%E6%8D%AE)
        - [返回数据](#%E8%BF%94%E5%9B%9E%E6%95%B0%E6%8D%AE)
    - [PUT - 更新用户资料](#put---%E6%9B%B4%E6%96%B0%E7%94%A8%E6%88%B7%E8%B5%84%E6%96%99)
        - [参数形式](#%E5%8F%82%E6%95%B0%E5%BD%A2%E5%BC%8F)
        - [上传数据](#%E4%B8%8A%E4%BC%A0%E6%95%B0%E6%8D%AE)
        - [返回数据](#%E8%BF%94%E5%9B%9E%E6%95%B0%E6%8D%AE)

# /user/profile
## GET - 获取user profile信息
### 参数形式
+ id = uuid

### 上传数据
无

### 返回数据
| 字段    | 类型        | 示例  | 说明       |
| ------- | ----------- | ----- | ---------- |
| errcode | Number      | 0     | 操作错误码 |
| user    | UserProfile | {...} | 返回的dig  |

## PUT - 更新用户资料
### 参数形式
+ id = UUID

### 上传数据
| 字段       | 类型   | 示例        | 说明     |
| ---------- | ------ | ----------- | -------- |
| lastname?  | String | "raregrass" | 用户姓氏 |
| firstname? | String | "raregrass" | 用户名字 |
| birthday?  | String | "2017-1-1"  | 用户生日 |

### 返回数据
| 字段    | 类型   | 示例 | 说明       |
| ------- | ------ | ---- | ---------- |
| errcode | Number | 0    | 操作错误码 |
