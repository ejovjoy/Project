# Project

Please extract Project.rar file
added sample database "laravel.sql" with this, import the same using mysql workbench 
 
 
 edit .env file as suitable to your System Settings
 
 */DataBase Settings*/
 
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
   
   
 */Mail Config Settings in .env file*/
 
    MAIL_DRIVER=smtp
    MAIL_HOST=smtp.gmail.com
    MAIL_PORT=25
    MAIL_USERNAME=mailcode07070@gmail.com
    MAIL_PASSWORD=mailcode07070#test#
    MAIL_ENCRYPTION=tls
    
  */Mail Config Settings in mail.php  file*/
  
  'from' => ['address' => 'mailcode07070@gmail.com', 'name' => 'Test'],
