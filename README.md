yum install curl-devel
yum install gd-devel

memcached from https://launchpad.net/libmemcached/1.0/1.0.16/+download/libmemcached-1.0.16.tar.gz
(--prefix=/usr)

memcachedphp from http://pecl.php.net/package/memcached/2.2.0


./configure --prefix=/opt/php5_6 --enable-static --enable-cli --enable-sockets --enable-shmop --enable-zip --with-curl --with-openssl --with-mysql --with-pdo-mysql --with-zlib --enable-bcmath -enable-calendar --enable-exif --with-gettext --with-gd --enable-mbstring --enable-pcntl --with-readline --enable-memcached --disable-memcached-sasl --disable-cgi --disable-opcache --without-pear

