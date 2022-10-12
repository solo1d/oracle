ORDER BY子句总是SELECT语句中的最后一个子句。

ORDER BY子句可在一列上应用一个函数，例如字符串函数，数学函数等，并按函数的结果对数据进行排序

```sql
select * from tabname  where 1 =1  order by 2 desc;  -- 按照第二个字段排序

select * from tabname  where 1 =1  order by 2 desc  NULLS FIRST;  -- 将null值放在第二个字段前面

select * from tabname  where 1 =1  order by 2 desc  NULLS LAST;  -- 将null值放在第二个字段后面

select * from tabname  where 1 =1  order BY UPPER( name ); -- 函数，排序时区分大小写

```



