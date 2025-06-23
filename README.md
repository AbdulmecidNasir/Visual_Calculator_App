# 🖩 C# Görsel Hesap Makinesi Uygulaması

## Proje Özeti

Bu proje, **C# Windows Forms** kullanılarak geliştirilmiş basit ve kullanıcı dostu bir **hesap makinesi uygulamasıdır**.  
Kullanıcılar, görsel butonlar aracılığıyla toplama, çıkarma, çarpma ve bölme işlemlerini kolayca gerçekleştirebilir.

## Proje Amacı

Amaç, **Windows Forms ortamında kullanıcı arayüzü geliştirme**, **buton event'leri kullanma** ve temel **aritmetik işlemleri programlama** pratiği yapmaktır.

## Özellikler

- Toplama, çıkarma, çarpma ve bölme işlemleri
- Buton tıklama olaylarıyla veri girişi
- Hata kontrolü (0’a bölme hatası için kullanıcı uyarısı)
- Ekranı sıfırlama butonu
- Sonuçların anlık ekrana yazdırılması

## 🛠️ Kullanılan Teknolojiler

- **C#**
- **.NET Framework**
- **Windows Forms**

##  Kod Açıklamaları

- `rakamButton_Click` metotları: Buton tıklamalarında ekrana rakam yazdırmayı sağlar.
- `artiButton_Click`, `eksiButton_Click`, `carpiButton_Click`, `bolmeButton_Click`: İşlem türünü belirler ve girilen ilk sayıyı kaydeder.
- `esittirButton_Click`: Girilen ikinci sayıyı alır, seçilen işleme göre sonucu hesaplar ve ekranda gösterir.
- `sifirlaButton_Click`: Hesap makinesinin ekranını sıfırlar.
- `if (_ekranTemizlenecekMi)` kontrolü: İşlem seçildikten sonra ekranı temizleyip yeni sayı yazmak için kontrol sağlar.
- Bölme işleminde `sayi2` değeri 0 ise hata mesajı gösterilir.

## 📸 Uygulama Görünümü

![Hesap Makinesi](https://github.com/AbdulmecidNasir/Visual_Calculator_App/blob/f88fa195bc825997b14521159d4a07bdc2921be6/screenshots/Screenshot%202025-06-23%20155523.png)
