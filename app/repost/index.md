# 目录
- [目录](#%E7%9B%AE%E5%BD%95)
- [/repost](#repost)
    - [POST - 进行一次repost](#post---%E8%BF%9B%E8%A1%8C%E4%B8%80%E6%AC%A1repost)
        - [可选参数形式](#%E5%8F%AF%E9%80%89%E5%8F%82%E6%95%B0%E5%BD%A2%E5%BC%8F)
            - [上传数据](#%E4%B8%8A%E4%BC%A0%E6%95%B0%E6%8D%AE)
            - [返回数据](#%E8%BF%94%E5%9B%9E%E6%95%B0%E6%8D%AE)

# /repost

## POST - 进行一次repost
### 可选参数形式
无

#### 上传数据
| 字段    | 类型     | 示例                                      | 说明                  |
| ------- | -------- | ----------------------------------------- | --------------------- |
| content | String   | "你好，我是你爸爸"                        | repost内容            |
| images  | String[] | ["http://image1.com","http://image2.com"] | repost中的配图        |
| refpost | String   | UUID                                      | 被repost的原始post id |

#### 返回数据
| 字段    | 类型   | 示例 | 说明       |
| ------- | ------ | ---- | ---------- |
| errCode | Number | 0    | 操作错误码 |
