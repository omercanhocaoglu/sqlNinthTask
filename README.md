# sqlNinthTask
## Bu repo [Patika.dev](https://www.patika.dev) tarafından verilen `SQL` ödevini içermektedir.
---
### Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.
### 1- city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
- SELECT country.country_id, country, city.city_id ,city FROM city
- INNER JOIN country ON country.country_id = city.city_id;
### 2- customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
- SELECT payment_id, first_name, last_name FROM customer
- INNER JOIN payment ON customer.store_id = payment.staff_id;
### 3- customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.
- SELECT rental_id, first_name, last_name FROM rental
- INNER JOIN customer ON rental.rental_id = customer.customer_id;
