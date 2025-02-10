Docker Image PHP harus dibuild terlebih dulu dimaksudkan agar tidak harus build ulang image jika ada kesalahan konfigurasi. jika sudah yakin baru bisa digabung. 

`docker build -t php-fpm-pr:8.2 .`


# Letakan file ini di root folder project

## untuk database anda bisa hubungkan dengan database host, atau membuat container baru

Jika dihubungkan dengan database/mariadb/mysql di host, kita perlu mengallow ip container docker 

`GRANT ALL PRIVILEGES ON psikotest.* TO 'USERNAME'@'IP_CONTAINER_' IDENTIFIED BY 'YOUR_PASSWORD';FLUSH PRIVILEGES;`


