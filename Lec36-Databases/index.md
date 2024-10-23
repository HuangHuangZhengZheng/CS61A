# Databases

## method of tables
### create and drop tables
![alt text](image.png)


:nerd_face:

![alt text](image-1.png)

```sql
create table numbers (n, note);
create table numbers (n UNIQUE, note DEFAULT 'unknown');
```

![alt text](image-2.png)
```sql
drop table if exists t;
```


### insert data into tables
![alt text](image-3.png)
```sql
insert into t values (1, 'one');
insert into t(col1) values (2);
```


