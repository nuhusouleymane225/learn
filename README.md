Invoke-WebRequest -Uri https://dl.google.com/cloudsql/cloud_sql_proxy_x64.exe -OutFile .\cloud_sql_proxy_x64.exe


.\cloud_sql_proxy_x64.exe -instances=ssms-vm=tcp:1433
