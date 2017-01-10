# docker-compose

Docker PHP development environment. 


### Quick Overview:

Let's install `NGINX`, `PHP 7.1`, `Composer`, `PostgreSQL`, `Redis` and `Beanstalkd`:

```shell
git clone https://github.com/Happensit/docker-compose.git Docker
```

```shell
cd Docker/
```

Check and edit docker-compose.yml file volumes level in the applications section

```shell
docker-compose up -d nginx postgres redis beanstalkd
```