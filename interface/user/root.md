# /user/login
## POST - 创建一个新用户
### 可选参数形式
无

#### 上传数据
```
{
    phone: string - 注册手机号码："13800138000"
    password: string - 注册密码："asdf234"
    referrer?: string - 推荐人ID："123df2143"
}
```

#### 返回数据
```
{
    _id: string - "234213sdrwe";
    icon: string - "http://url.com";
    name: string - "面团儿sdf2143sdf";
    gender: string - "male";
    prefer: string[] - ["xmt"];
}
```

#### 错误处理
```
{
    
}
```
