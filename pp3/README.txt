Local Setup Instructions:

0) required software: php >=5.6 cli, web server with php >=5.6 (apache, nginx...), mysql >=5.7, composer 
1) clone project
2) in root folder run $ composer install
3) copy over config .dist files and set proper values there 
	config/autoload/
	module/Application/config/
4) setup local database with config/pp3.sql script
5) to become admin user add your google email into module/Application/config/module.config.php: pp3->admin property 
6) open pp3/public/ folder in teh browser to see the application
7) set write access to data/ and public/data folders so app can store files
