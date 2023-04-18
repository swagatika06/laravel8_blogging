# laravel8_blogging

prerequisites:

php:8

mysyl

laravel:8

Set up :

Clone the repo and cd into it
    git clone https://github.com/swagatika06/laravel8_blogging.git
    
Rename or copy .env.example file to .env

create database laravel8_blog

In your terminal composer install

php artisan key:generate

Set your database credentials in your .env file

php artisan migrate

php artisan storage:link//to view uploade image @local setup

php artisan db:seed(optional)//to populate fake data in db

or

php artisan db:seed --class=PostsTableSeeder

php artisan db:seed --class=CategoriesTableSeeder

php artisan db:seed --class=TagsTableSeeder

php artisan serve

Landing Page:

![image](https://user-images.githubusercontent.com/73284415/232777988-6343a609-cc66-4830-851c-08aaea9a65c1.png)

Registration Page:

![image](https://user-images.githubusercontent.com/73284415/232778269-41ac4826-58ec-4bed-af00-a5add8f7021c.png)

Login Page:

![image](https://user-images.githubusercontent.com/73284415/232778396-79f555f8-7966-483a-8406-1c60ca83c573.png)


User Dshboard Page:

![image](https://user-images.githubusercontent.com/73284415/232738613-a66bc621-5c45-45b4-a91d-04b1a7610246.png)

Add Category:

![image](https://user-images.githubusercontent.com/73284415/232773155-97d9c73c-5ed1-4aac-b119-ac775bbe95a9.png)

Add Post:

![image](https://user-images.githubusercontent.com/73284415/232774641-bc5b406e-f630-4846-ba81-b172b9fce36d.png)

Filter based on Category

![image](https://user-images.githubusercontent.com/73284415/232774854-32084329-8731-491a-b975-022d3feb88c5.png)

Search based on Keyword

![image](https://user-images.githubusercontent.com/73284415/232775262-6debd863-7ed1-4ef5-98d5-562a5a402245.png)

Postman Snippet:
1. Get All Posts:

![image](https://user-images.githubusercontent.com/73284415/232776588-9bfda3e3-1ab5-4e7c-98e1-20af79db3215.png)


2. Get Post by Slug Id
![image](https://user-images.githubusercontent.com/73284415/232776793-ca85e100-c57c-480a-9b6e-e685d1bf93e0.png)


