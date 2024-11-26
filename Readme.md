## Installation and setup 

Clone Repository 
```
git clone https://github.com/Drooggie/template-docker-laravel.git
``` 

Move into Repository 
```
cd template-docker-laravel
``` 


Run this command for building and starting containers
```
docker compose up -d --build
```  
<br />

Run this commands for migration:
```
docker exec qortex_app php artisan migrate:fresh --seed --force
```
