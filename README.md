# ShopBridge
Dear all follow the following steps to use this Web Application locally
Steps :
      1) Download and copy all the files including folder to C:\inetpub\wwwroot
      2) Open Items SQL.text file and copy the code, goto mysql, sql command line and paste in paste the code, which will create a table name items
      3) open the web.config file and change the connection string with Database , Uid and Pwd
           <connectionStrings>
    <add name="mysql" connectionString="server=localhost;Port=3306;Database=...;Uid=....;Pwd=....;pooling=false" providerName="System.Data.MySqlClient"/>
  </connectionStrings>
    4) open web browser and type localhost
