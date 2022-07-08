Invoke-WebRequest -Uri https://dl.google.com/cloudsql/cloud_sql_proxy_x64.exe -OutFile .\cloud_sql_proxy_x64.exe


.\cloud_sql_proxy_x64.exe -instances=qwiklabs-gcp-04-1fcd07ce39f6:us-central1:myinstance=tcp:1433

qwiklabs-gcp-04-1fcd07ce39f6:us-central1:myinstance
