## 注意事项

1. 数据库版本为```Mysql 8.0.25```。

2. 在使用前需用```scr/config```中提供的sql脚本```StudentSystem.sql```来创建一个数据库。

3. 连接数据库所需的配置信息在```scr/config```中的```config.properties```中填写。

4. 按钮点击反应不是很灵敏，有时需要多次点击。

## 运行方法

运行```scr/main```中的```main.java```。

## 主要功能

在学生模块中可以执行添加学生、删除学生、查询成绩、选退课操作。

在课程模块中可以执行添加课程、删除课程、查询选课学生、登分操作，其中登分操作包含在查询选课学生中。

