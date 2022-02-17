## Firmalar için unvan, tarih ve vergi numarası kayıtlarını ekleyen, okuyan, güncelleyen ve silen, ADO.NET ve ASP.NET CORE kullanarak tasarlanmış WEB uygulaması

## Veri tabanı için:

CREATE DATABASE firmaKayit;
---
CREATE TABLE firma (
    FID int NOT NULL PRIMARY KEY,
    unvan varchar(50),
    tarih smalldatetime,
    vkn varchar(50)
);
---
 
