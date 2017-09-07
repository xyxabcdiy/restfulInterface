# 目录
- [目录](#目录)
- [/admin/user/count](#adminusercount)
    - [GET - 得到用户统计](#get---得到用户统计)
        - [可选参数形式](#可选参数形式)
            - [上传数据](#上传数据)
            - [返回数据](#返回数据)

# /admin/user/count

## GET - 得到用户统计
### 可选参数形式
+ filter = all | active | lock | dead

#### 上传数据
无

#### 返回数据
| 字段    | 类型   | 示例  | 说明       |
| ------- | ------ | ----- | ---------- |
| errcode | Number | 0     | 操作错误码 |
| count   | Number | 99999 | 用户总数   |