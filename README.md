## Symfony kullanmanın avantajları nedir? Kendi cümlelerinizle açıklayınız.
PHP için kullanılabilicek en iyi frameworklerden biridir. 
Açık kaynak kodlu olması ve MVC modeli ile kullanımı rahattır. 

## Symfony ile environment (ortam) ayarlaması nasıl yapılır?
.env dosyasındaki 'APP_ENV' bölümünü ile ayarlanır. Eğer dev olarak ayarlanacaksa, 'APP_ENV=dev' yazılır.
Eğer prod olarak ayarlanacaksa, 'APP_ENV=prod' yazılır.

## Yeni bir Symfony projesi oluşturmak için kullanılan composer komutu nedir? Alternatif bir komutla Symfony projesi oluşturabilir miyiz?

### Composer üzerinden proje kurmak için kullanılan komut şudur:

composer create-project symfony/skeleton:"^5.4" my_project_directory

### alternatif olarak:
symfony new my_project_directory --version=5.4 --webapp

## Laravel framework ve Symfony framework arasındaki temel farklardan iki tanesini yazınız.
Aslında iki de birbirine yakındır fakat symfony büyük projeler için daha kullanışlıdır.
Paket konusunda laravel daha zengin olsa da symfony özelleştirme ve kodlama için daha kullanışlıdır.
