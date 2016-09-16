# NorthwindDb

This is Empty ASP.NET Web API project, include Northwind Database and setting.

Select one connectionStrings in Web.config:

```xml
  <connectionStrings>
    <!-- SQL Express -->
    <add name="Northwind" connectionString="data source=.\sqlexpress;initial catalog=Northwind;integrated security=True;MultipleActiveResultSets=True;App=EntityFramework" providerName="System.Data.SqlClient" />
    <!-- SqlLocalDb -->
    <add name="Northwind" connectionString="data source=(LocalDB)\MSSQLLocalDB;attachdbfilename=|DataDirectory|\Northwind.mdf;integrated security=True;MultipleActiveResultSets=True;App=EntityFramework" providerName="System.Data.SqlClient" />
  </connectionStrings>
```
