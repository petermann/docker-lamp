# docker-lamp

Docker with Apache, MariaDB 10.3.18, phpMyAdmin and Php 7.4

I use docker-compose as an orchestrator. To run these containers:

```
docker-compose up -d
```

Open phpMyAdmin at [http://localhost:3001](http://localhost:3001)  
Open web browser to look at a simple php example at [http://localhost:3000](http://localhost:3000)  

Run mysql client:

- `docker-compose exec db mysql -u root -p` 

Enjoy !
