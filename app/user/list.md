# 目录
- [目录](#%E7%9B%AE%E5%BD%95)
- [/user/list](#userlist)
    - [GET - 获取用户列表](#get---%E8%8E%B7%E5%8F%96%E7%94%A8%E6%88%B7%E5%88%97%E8%A1%A8)
        - [参数形式](#%E5%8F%82%E6%95%B0%E5%BD%A2%E5%BC%8F)
        - [上传数据](#%E4%B8%8A%E4%BC%A0%E6%95%B0%E6%8D%AE)
        - [返回数据](#%E8%BF%94%E5%9B%9E%E6%95%B0%E6%8D%AE)

# /user/list
## GET - 获取用户列表
### 参数形式
+ sort= rank | date
+ start = 0
+ count = 10
+ [ tag = nodejs & tag = xmt & tag = battle ]
+ [ label = official & good & lala ]

### 上传数据
无

### 返回数据
| 字段     | 类型               | 示例 | 说明       |
| -------- | ------------------ | ---- | ---------- |
| errCode  | Number             | 0    | 操作错误码 |
| profiles | Object \| Object[] | [{}] | 用户列表   |
