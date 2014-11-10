#support Mongodb,Mysql,Hbase,ES .... ,And there Sql'result to redis cache .

```
from sqltocache import cache_it_json

@cache_it_msgpack(cache=self.c)
def add_it(a, b=10, c=5):
    return a + b + c
add_it(3)
```

ToDo:
    1. 尽量多的兼容二次的序列化

    2. 缓存的web api
