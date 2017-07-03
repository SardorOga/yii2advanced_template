Yii2 advanced template.

Separate Frontend and Backend to use different tables (landing page/admin).

** This template is working only on Apache web server.

Virtual host config:

<VirtualHost *:80>

    ServerName yii2.loc
    DocumentRoot "D:Apache/home/yii2.loc"
    <Directory "/">
        DirectoryIndex  index.php index.html
        AllowOverride All
    </Directory>
	
</VirtualHost>

Main website url :  http://yourdomain.com
Admin url        :  http://yourdomain.com/admin

