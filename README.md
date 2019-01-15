# Docker LEMP stack example

Docker compose LEMP stack example. Based on the PentaCode tutorial:
https://github.com/yongzhihuang/PentaCode/tree/master/DockerLEMP 
https://www.youtube.com/watch?v=M1j41ud2O-M
 
I have fixed some of the bugs present in the original tutorial (some problems with the nginx 
conf and the phpmyadmin box).

The phpmyadmin box MUST have the PMA_HOST and PMA_PORT environment variables 
set in order work correctly. Also the variables PMA_PASSWORD (on the phpmyadmin service) and the MYSQL_ROOT_PASSWORD (on the mysql service) must be the same. PMA_USER must be root or a prexisting mysql user.

  

