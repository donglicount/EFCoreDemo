1.配置实体类 
2.安装Microsoft.EntityFrameworkCore.SqlServer：nuget命令 Install-Package Microsoft.EntityFrameworkCore.SqlServer -version 5.0
3.创建实现了IEntityTypeConfiguration接口的实体配置类，配置实体类和数据库表的对应关系
4.创建上下文类DbContext
5.安装Microsoft.EntityFrameCore.Tools
6.命令  Add-Migration InitialCreate 生成数据库代码
7.命令 Update-Database 生成数据表