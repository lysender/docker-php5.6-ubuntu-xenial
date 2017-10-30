# Docker for Ubuntu 16.04 with PHP 5.6.x

## Usage for local development

~~~
sudo docker run --name "sample-web" \
    -d \
    -p 8080:80 \
    -v /my/host/project-log-dir:/var/log/apache2 \
    -v /my/host/project-public-dir:/var/www/html \
    --env-file /my/host/project-env-file \
    lyender/php5.6-ubuntu-xenial;
~~~
