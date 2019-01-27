# WhatsActivator Api Documentation

# Api endpoint
https://whatsactivator.com/api/ **APIKEY** / **SERVIS**

# Ön bilgi
**APIKEY** inize müşteri panelinizde ki APİ sekmesinden ulaşabilirsiniz.


# Servisler

Metod | SERVIS | Açıklama
------------- | ------------- | -------------
POST | SendCode | Numaraya rastgele bir doğrulama kodu gönderir.
POST | SendSpecialCode | Numaraya sizin belirlediğiniz bir doğrulama kodu gönderir.

# Service Post Fields

## SendCode Servisi

Input | Durum | Açıklama
------------- | ------------- | -------------
number | Gerekli | Mesaj atılacak kişinin numarası

## SendSpecialCode Servisi

Input | Durum | Açıklama
------------- | ------------- | -------------
number | Gerekli | Mesaj atılacak kişinin numarası
code | Gerekli | Gönderilecek mesaj(min : 3, max : 8 karakter)
