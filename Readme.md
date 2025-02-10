# Letakan file ini di root folder project

## untuk database anda bisa hubungkan dengan database host, atau membuat container baru

Jika dihubungkan dengan database/mariadb/mysql di host, kita perlu mengallow ip container docker 

`GRANT ALL PRIVILEGES ON psikotest.* TO 'USERNAME'@'IP_CONTAINER_' IDENTIFIED BY 'YOUR_PASSWORD';FLUSH PRIVILEGES;`


