### Set up :

1. Clone the repository
2. ```composer install```
3. Rename or copy ```.env.example``` file to ``.env``
4. php artisan key:generate
5. Set the database credentials in the ```.env``` file
6. Set the Braintree credentials in the ```.env``` file
7. Import db file (```database/e-shop.sql```) into the database (```mysql,sql```)
8. ```npm install```
9. ```npm run watch```
10. run command[laravel file manager]:-  ```php artisan storage:link```
11. Edit ```.env``` file :- remove APP_URL
10. ```php artisan serve``` or use virtual host
11. Visit ```localhost:8000``` in your browser
12. Visit /admin if you want to access the admin panel. Admin Email/Password: ```admin@gmail.com```/```1111```. User Email/Password: ```user@gmail.com```/```1111```


### Screenshots :
![screencapture-e-shop-loc-admin-2020-08-15-15_47_37](https://user-images.githubusercontent.com/29488275/90719413-13b82200-e2d4-11ea-8ca0-f0e5551c4c9d.png)