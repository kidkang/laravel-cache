# 1.set(key,value,[expire])

##option

### key 存储的键名

### value 值
>string|array

如果是array 会用json_encode 转换为字符串

### expire 单位分钟
> 过期时间，如果不穿，表示永久缓存
> 
# 2.get(key)
>获取缓存
如果存入为数组，返回也为数组