server {
listen 80;
server_name 20.232.107.138;

location /static{
alias /home/azureuser/flaskApp/static/;
}

location / {
  include proxy_params;
  proxy_pass http://unix:/home/azureuser/flaskApp/app.sock;
    }
}
