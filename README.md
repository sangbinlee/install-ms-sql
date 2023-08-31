# install-ms-sql



# compose.yml

    services:
      sqlserver:
        image: 'mcr.microsoft.com/mssql/server:latest'
        environment:
          - 'ACCEPT_EULA=yes'
          - 'MSSQL_PID=express'
          - 'MSSQL_SA_PASSWORD=verYs3cret'
        ports:
          - '1433'



![image](https://github.com/sangbinlee/install-ms-sql/assets/4024414/b7ce2448-cf80-48aa-b292-cfdfe81799c5)




  ![image](https://github.com/sangbinlee/install-ms-sql/assets/4024414/e3422bec-c14e-4bc3-b182-ea0d58097a46)



![image](https://github.com/sangbinlee/install-ms-sql/assets/4024414/cf7efe52-3f7a-4524-b279-002d79e39130)
