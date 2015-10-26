mysql
------------------------------------------------------------

# 
FROM http://www.pyrasis.com/ --  MYSQL CONTAINTER Base

-------------------------------------------------------------
#
Use
-------------------------------------------------------------
EX) sudo docker run -p 3306:3306 -v /home/mysql/:/var/lib/mysql -i -t -d --name db -e MYSQL_ROOT_PASSWORD='examplepassword' henen/mysql

