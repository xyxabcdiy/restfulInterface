# 目录
- [目录](#%E7%9B%AE%E5%BD%95)
- [/placeholder](#placeholder)
    - [GET - 用户个数统计](#get---%E7%94%A8%E6%88%B7%E4%B8%AA%E6%95%B0%E7%BB%9F%E8%AE%A1)
        - [可选参数形式](#%E5%8F%AF%E9%80%89%E5%8F%82%E6%95%B0%E5%BD%A2%E5%BC%8F)
            - [上传数据](#%E4%B8%8A%E4%BC%A0%E6%95%B0%E6%8D%AE)
            - [返回数据](#%E8%BF%94%E5%9B%9E%E6%95%B0%E6%8D%AE)

# /placeholder

## GET - 用户个数统计
### 可选参数形式
+ filter = all | active | lock | dead

#### 上传数据
无

#### 返回数据
| 字段    | 类型   | 示例  | 说明       |
| ------- | ------ | ----- | ---------- |
| errcode | Number | 0     | 操作错误码 |
| count   | Number | 99999 | 用户总数   |