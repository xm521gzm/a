### 创建用户 授予权限

```
mysql -u root -h 127.0.0.1  -P 3307 -p

create user 'xhf_article'@'%' identified by 'K3kf43.1~~SrAr';
grant all privileges ON xhf.f_article to  'xhf_article'@'%'; 

grant all privileges on *.* to 'root'@'%' identified by 'NcAGFryS7nNrn27Aa';

revoke all privileges on bag.* from  'xhfy'@'180.78.189.161'; #去除权限
drop user hsh@'103.238.134.52';

create user 'wxbyc'@'61.149.%.%' identified by '8wxb.y1c.B5+H1G';
grant all privileges ON wxb.* to  'wxbyc'@'61.149.%.%'; 

CREATE DATABASE battery DEFAULT CHARSET utf8 COLLATE utf8_general_ci;

create user 'battery'@'103.238.134.52' identified by 'batteryahuaryAc';
grant all privileges ON battery.* to  'battery'@'103.238.134.52'; 
```