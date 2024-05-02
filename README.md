# cloudera
**open terminal 
> hostname
> hdfs dfs -ls
> sudo /home/cloudera/cloudera-manager --express --force
**open browser
/7180 in search tab press enter
username and pass
right corner Action > restart > close
**open cmd
cat > /home/cloudera/pratik.txt(filename.txt)
cat  /home/cloudera/pratik.txt
1~pratik~akluj~student
hdfs dfs -ls
hdfs dfs -put pratik.txt
hdfs dfs -ls /user/cloudera
hive
show databases;
create database pratik;
show databases;
use pratik;
show tables;
create table info(id int,name string,city string,status string)
> row format delimited fields terminated by'~';

show tables;
load data inpath'/user/cloudera/info.txt'overwrite into table info;
select*from info;

**hive commands to alter table
desc info;
select name,city from info;
alter table info rename to details;
show tables;
select*from details;
alter table details add columns(dept string);
select*from details;

cont+z to exit
