# flaskApp
Flask app will convert long url to short url

- **Install nginx and python**
- Install all required packages
- Create Virtual environment and activate it
- Install gunicorn
- Create wsgi file
- Create Systemd service file ( add this file /etc/systemd/system/  
- Run the command  the system using command systemctl start app       
- It will create app.sock file
- Create app file and add it /etc/nginx/sites-available/
- Restart Nginx
- You should be able to access your add @server_ip
