# dob-2017-oct-exam
Set of three Docker containters (nginx, php, mysql) that form a simple web application

Please note that:
 - each container should be named after the following rule - dob-role, where role is php, mysql, or nginx;
 - mysql password is expected to be Password1;
 - nginx is set to listen on port 80;
 - php files are expected to be in the /site folder of both nginx and php containers;
 - nginx container should be started after php;
