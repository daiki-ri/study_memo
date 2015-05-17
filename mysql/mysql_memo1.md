#Mysqlで◯秒以上かかっているクエリを抽出

例 : 1秒以上かかっているクエリ抽出

```
SELECT * FROM information_schema.PROCESSLIST WHERE TIME > 1;
```
