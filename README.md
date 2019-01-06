# udemy_rails
for study rails by Udemy

Ruby: 2.3.5
Rails: 5.0.0.1
MySQL: 5.7

1.create new app
```
$ docker-compose run web rails new . --forcce --database=mysql
$ docker-compose build 
```

2. edit database.yml
```
edit password and host
```

3.start
```
$ docker-compose up -d

// check
$ docker-compose ps
```
4.db create
```
$ docker-compose run web bundle exec rake  db:create
```
