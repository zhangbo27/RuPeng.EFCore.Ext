# RuPeng.EFCore.Ext
use modelBuilder.Configurations.AddFromAssembly() in Entity Framework Core 2.0

Entity Framework Core 2.0中提供了IEntityTypeConfiguration，不过没有提供EF中的 modelBuilder.Configurations.AddFromAssembly()，因此这里提供了一个而类似的实现，用法：
```
modelBuilder.ApplyConfigurationsFromAssembly(asmServices);
```
安装方法：
>Install-Package RuPeng.EFCore.EntityTypeConfig
 
#此开发包由如鹏网杨中科老师开发，学中国最牛逼的.Net课程，到[如鹏网](http://www.rupeng.com)！
