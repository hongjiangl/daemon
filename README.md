
不支持windows哦

[https://www.cnblogs.com/iforever/p/9039579.html](https://www.cnblogs.com/iforever/p/9039579.html)

## 使用
```
php test/test.php start
```

```
php test/test.php status
```
输出：
```
Daemon [Test] 信息:
-------------------------------- master进程状态 --------------------------------
pid       占用内存       处理次数       开始时间                 运行时间
35216     2M             --             2018-05-15 02:06:18      0 天 0 时 3 分
6 slaver
-------------------------------- slaver进程状态 --------------------------------
任务task-mcq:
35217     2M             24             2018-05-15 02:06:18      0 天 0 时 3 分
35218     2M             24             2018-05-15 02:06:18      0 天 0 时 3 分
--------------------------------------------------------------------------------
任务other:
35219     2M             46             2018-05-15 02:06:18      0 天 0 时 3 分
35220     2M             46             2018-05-15 02:06:18      0 天 0 时 3 分
35221     2M             46             2018-05-15 02:06:18      0 天 0 时 3 分
35222     2M             46             2018-05-15 02:06:18      0 天 0 时 3 分
--------------------------------------------------------------------------------
```


## 待完善
1. 日志模块儿
2. 进程各种状态记录详细日志
