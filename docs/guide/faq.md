# FAQ

> Q：这个系统的数据安全吗？

A：后端使用的Django也是一个经过多年迭代的成熟框架。数据库采用的是阿里云的关系型云数据库RDS，支持MySQL、SQL Server、PostgreSQL、MariaDB和PPAS引擎，具备容灾、备份、恢复、迁移等方面的全套解决方案，大厂品质值得信赖。



> Q：怎样备份数据？

A：在管理页面，所有数据表都有导出数据的选项，可以导出Excel、csv、json、yaml等8种格式的文件。未来可能会新增 导出类似于V1课表的Excel 的功能（待定）。



> Q：如何适应**培养方案变更**的情况的？

A：每学期都有对应的“学期戳”，每学期都会根据已有信息生成**专属的培养方案和教学计划**，可以根据实际情况改动。这样的设计让未来的改动不会影响已有的课表记录。