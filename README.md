# Xiaomi Takvim Web Uygulaması

BLM4581 Ağ Tabanlı Teknolojiler ve Uygulamaları
dersi için geliştirilen takvim yönetim sistemi.

## Teknolojiler

- ASP.NET Core MVC (.NET 10)
- ASP.NET Core Web API
- PostgreSQL 18
- Entity Framework Core
- HTML, CSS, JavaScript, Bootstrap

## Proje Yapısı

- src/Takvim.Web: Web arayüzü
- src/Takvim.Api: REST API
- Takvim.slnx: Çözüm dosyası

## Geliştirme Ortamı

- Windows 11
- WSL 2 / Ubuntu
- .NET 10 SDK
- PostgreSQL 18

## Çalıştırma

Web uygulaması:

cd src/Takvim.Web
dotnet run

API uygulaması:

cd src/Takvim.Api
dotnet run

## Veritabanı

PostgreSQL üzerinde takvim_db veritabanı kullanılır.

Bağlantı bilgileri .NET User Secrets ile saklanır.

## Planlanan Özellikler

- Kullanıcı kayıt ve giriş işlemleri
- Günlük, haftalık ve aylık takvim
- Etkinlik CRUD işlemleri
- Kategori ve hatırlatıcı yönetimi
- Yönetici paneli
- Rol bazlı yetkilendirme
