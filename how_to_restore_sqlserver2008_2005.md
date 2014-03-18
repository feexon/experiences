#如何还原SQLServer2008到SQLServer2005

1.	[下载 Database Publishing Wizard](http://www.microsoft.com/downloads/details.aspx?FamilyId=56E5B1C5-BF17-42E0-A410-371A838E570A&displaylang=en)
2.	安装**Database Pubishing Wizard**
3.	设置**PATH=%DATABASE_PUBLISH_WIZARD_BIN%;%PATH%**
4.	执行sqlpubwiz script -d **sqlserver2008:db** C:\FooDB.sql
5.	执行sqlcmd -S . -d **sqlserver2005:db** -i c:\FooDB.sql
