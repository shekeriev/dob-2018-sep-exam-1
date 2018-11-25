# dob-2018-sep-exam-1
Set of three Docker containters each with dedicated role - php, mysql, and nginx, that form a simple web application.

For a successful completion you have to:
 - (re)build the images;
 - (re)run the containers;
 - mount the /site component where applicable;

Please note that:
 - each container should be named after the following rule - **dob-role**, where role is *php*, *mysql*, or *nginx*;
 - mysql password is expected to be **1q2w3e4r**;
 - nginx is set to listen on port **80**;
 - php files are expected to be in the **/site** folder of both nginx and php containers;
 - nginx container should be started after php;
