# 目录
- [目录](#目录)
- [/admin/login](#adminlogin)
    - [POST - 管理员登录](#post---管理员登录)
        - [可选参数形式](#可选参数形式)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)

# /admin/login
## POST - 管理员登录
### 可选参数形式
无

#### 上传数据
| 字段       | 类型   | 示例      | 说明       |
| ---------- | ------ | --------- | ---------- |
| employeeId | Number | 12312313  | 管理员工号 |
| password   | String | "FASDFSF" | 管理员密码 |

#### 返回数据
| 字段    | 类型   | 示例 | 说明       |
| ------- | ------ | ---- | ---------- |
| errcode | Number | 0    | 操作错误码 |