# Bookstore-Management-Studio
江南大学数据库课设
# BookStore
BookStore说明文件
Orion-wyc  计科1604 物联网工程学院 江南大学

本项目文件结构如下：
计科1604_书店销售管理系统_1030416414_王宇晨
	数据库文件
	（包含五个文件，其中.bak是备份数据库文件，.mdf是数据库文件，.LDF是日志文件，以及一份创建数据库的脚本文件）
	# 数据导入采用如下SQL命令：
	EXEC  sp_attach_db  @dbname  =  'BOOKSTORE',     --输入数据库名称
	@filename1  =  'G:\暂存\数据库课程设计\bookstoreC#\bookstore\DataBase\BOOKSTORE.mdf',  --输入文件绝对路径   
	@filename2  =  'G:\暂存\数据库课程设计\bookstoreC#\bookstore\DataBase\BOOKSTORE_log.LDF'

	系统文档
	（包含五个文件，其中四个已提交）

	系统源程序
	包含项目所有源代码，未编译生成解决方案，其中有一份打包成可执行文件的应用程序（位置如下），可直接运行。具体配置见下：
	"计科1604_书店销售管理系统_1030416414_王宇晨\系统源程序\书店销售系统 version 1.0.2\Debug\bookstore.exe"
	（1）本项目采用C#开发，实现的功能详见课程设计报告。可使用VS 2016/VS Code打开。
	（2）数据库使用SQL Server Express 2014，无法实现远程连接，仅可在本机使用。
	     如果想要在其他电脑上运行，请修改“CONN.cs”文件。
完整项目文件参见：https://github.com/Orion-wyc/Bookstore-Management-Studio
