# 目录
- [目录](#目录)
- [/admin/user/status](#adminuserstatus)
    - [PUT - 修改用户状态](#put---修改用户状态)
        - [可选参数列表](#可选参数列表)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)

# /admin/user/status
## PUT - 修改用户状态
### 可选参数列表
+ id = UUID

#### 上传数据
| 字段         | 类型   | 示例   | 说明               |
| ------------ | ------ | ------ | ------------------ |
| targetStatus | String | "lock" | 用户将要变成的状态 |

#### 返回数据
| 字段    | 类型   | 示例 | 说明       |
| ------- | ------ | ---- | ---------- |
| errcode | Number | 0    | 操作错误码 |