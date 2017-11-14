# 目录
- [目录](#%E7%9B%AE%E5%BD%95)
- [/verify/email](#verifyemail)
    - [POST - 请求邮箱验证](#post---%E8%AF%B7%E6%B1%82%E9%82%AE%E7%AE%B1%E9%AA%8C%E8%AF%81)
        - [参数形式](#%E5%8F%82%E6%95%B0%E5%BD%A2%E5%BC%8F)
        - [上传数据](#%E4%B8%8A%E4%BC%A0%E6%95%B0%E6%8D%AE)
        - [返回数据](#%E8%BF%94%E5%9B%9E%E6%95%B0%E6%8D%AE)

# /verify/email
## POST - 请求邮箱验证
### 参数形式
无

### 上传数据
| 字段  | 类型   | 示例                       | 说明     |
| ----- | ------ | -------------------------- | -------- |
| email | String | "sevenryze@deepdigest.com" | 用户邮箱 |

### 返回数据
| 字段    | 类型   | 示例 | 说明       |
| ------- | ------ | ---- | ---------- |
| errcode | Number | 0    | 操作错误码 |
