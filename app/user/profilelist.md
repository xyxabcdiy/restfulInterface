# 目录
- [目录](#%E7%9B%AE%E5%BD%95)
- [/user/profilelist](#userprofilelist)
    - [GET - 获取user profile列表](#get---%E8%8E%B7%E5%8F%96user-profile%E5%88%97%E8%A1%A8)
        - [参数形式](#%E5%8F%82%E6%95%B0%E5%BD%A2%E5%BC%8F)
        - [上传数据](#%E4%B8%8A%E4%BC%A0%E6%95%B0%E6%8D%AE)
        - [返回数据](#%E8%BF%94%E5%9B%9E%E6%95%B0%E6%8D%AE)

# /user/profilelist
## GET - 获取user profile列表
### 参数形式
+ sort= rank | date
+ start = 0
+ count = 10
+ [ tag = nodejs & tag = xmt & tag = battle ]
+ [ label = official & good & lala ]

### 上传数据
无

### 返回数据
| 字段     | 类型               | 示例    | 说明              |
| -------- | ------------------ | ------- | ----------------- |
| errcode  | Number             | 0       | 操作错误码        |
| profiles | UserProfileBrief[] | [{...}] | 返回的profile列表 |
