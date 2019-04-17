# PMS-WEB-APi/Database
Download SQL Server Management Studio, connect met windows authentication.
Kopieer de query uit DBscript.txt en plak hem in New Query(in MSSMS om de database aan te maken.
Voeg jouw Database Server Name, dataSource toe in Web.config file.
   Voorbeeld van mijne <add name="ConnString" connectionString="Data Source=LAPTOP-08SJQA4K; Initial Catalog= PMS;persist security info=True; Integrated Security=SSPI" providerName="System.Data.SqlClient"/>
Build Project
Run Project.
