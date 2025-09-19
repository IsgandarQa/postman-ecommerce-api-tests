##(AZ) E-Ticarət platforması üçün api test nə avtomatlaşdırma layihəsi. 

Bu layihə Postman istifadə edərək e-ticarət (fakestoreapi.com) api-yın test etmək və avtomatlaşdırmaq üçün yaradılan testlər toplusudur.
Layihə avtorizasiyanı məhsul siyahısını və cavabların doğruluöunu yoxlayır.

##TEST EDİLƏN ƏSAS FUNKSİONALLIQLAR 
*Avtorizasiya*-'Post/auth/login' sorğusu ilə token alınması və ovtomatik olaraq bir dəyişənə yazılması.
*Məhsullar*-'Get/products' sorğusu ilə bütün məhsulların siyahısının alınması və cavabların doğruluğunun (status kodu məzmununun boş olmaması) yoxlanması.

##NECƏ İSTİFADƏ EDƏ BİLƏRSİZ?
1.Bu repozitoriyadakı 'jason' fayıllarını öz Postman proqramınıza 'import' edin.
2.FakeStore-Production mühitini aktivləşdirin.
3.Avtorizasiya (Auth) kolleksiyasından Login sorğusunu bir dəfə işə salın ki token yadda saxlanılsın 
4.digər sorğuları icra edin.



##(EN) API test automation project for an e-commerce platform 

This project contains an automation test suite for an e-commerce api (fakestoreapi.com) built using Postman.It covers authentication product listing, and response validation.



##Key Features Tested:
*User Authentication* 'post/auth/login'
*Product Listing* 'Get/products'


##How to use 
1.Import the COllection and Envitoment 'json' files into your Postman application.
2.Select the 'FakeStore-Production' enviroment.
3.Run the 'Login' from the 'Auth'collection first to obtain and save the token.
4.Run other requests.


