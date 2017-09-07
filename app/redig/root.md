# 目录
- [目录](#目录)
- [/redig](#redig)
    - [POST - 进行一次redig](#post---进行一次redig)
        - [可选参数形式](#可选参数形式)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)

# /redig

## POST - 进行一次redig
### 可选参数形式
无

#### 上传数据
| 字段    | 类型     | 示例                                      | 说明                |
| ------- | -------- | ----------------------------------------- | ------------------- |
| content | String   | "你好，我是你爸爸"                        | redig内容           |
| images  | String[] | ["http://image1.com","http://image2.com"] | redig中的配图       |
| refdig  | String   | UUID                                      | 被redig的原始dig id |

#### 返回数据
| 字段    | 类型   | 示例 | 说明       |
| ------- | ------ | ---- | ---------- |
| errcode | Number | 0    | 操作错误码 |
