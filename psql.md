## 注释

```sql
postgres=# select $$who u r$$;
 ?column? 
 who u r
(1 row)

```



## 计算

```SQL
postgres=# select 100+123;
 ?column? 
----------
      223
(1 row)

postgres=# 
```





## 类型转换

```sql
postgres=# select '5'::int;
int4 
5
(1 row)
postgres=# 
```


## 大小写转换

```sql
SELECT concat_lower_or_upper('Hello', 'World', true);
concat_lower_or_upper
-----------------------
HELLO WORLD
(1 row)

All arguments are specified in order. The result is upper case since uppercase is specified as true.

Another example is:
SELECT concat_lower_or_upper('Hello', 'World');
concat_lower_or_upper
-----------------------
hello world

(1 row)
```

