# OgrenciBilgiSistemi

🎓 Öğrenci Bilgi Sistemi
Bu proje, Fırat Üniversitesi Bilgisayar Mühendisliği bölümü Nesne Tabanlı Programlama (OOP) dersi kapsamında geliştirilmiş bir öğrenci bilgi yönetim sistemidir. Uygulama; öğrencilerin ders kayıtlarını yapabilmeleri, notlarını görebilmeleri ve transkriptlerini görüntüleyebilmeleri amacıyla tasarlanmıştır.

🎯 Projenin Amacı
Bu sistemin temel amacı, üniversite ortamında öğrenci ve ders takibini dijitalleştirmektir. Geliştirilen sistem sayesinde:

Öğrenciler ders kaydı yapabilir,

Akademisyenler öğrencilere ait not girişlerini gerçekleştirebilir,

Öğrenciler, aldıkları dersler ve not bilgilerine göre transkript çıktısı alabilir.

Bu sayede kullanıcı dostu bir arayüzle eğitim süreçleri kolaylaştırılmış ve akademik verilerin yönetimi daha verimli hale getirilmiştir.

🏗️ Kullanılan OOP (Nesne Tabanlı Programlama) Kavramları

🔹 Sınıf ve Nesne Kullanımı

Sistemde üç temel sınıf kullanılmıştır:

Ogrenci sınıfı, öğrenciye ait kimlik, numara, kayıtlı dersler gibi bilgileri tutar.

Ders sınıfı, ders adını, kodunu, kredisini ve türünü içerir.

Not sınıfı ise öğrencilerin derslerine ait sınav notlarını ve bu notların ortalamalarını barındırır.

🔹 Kalıtım (Inheritance)

Ders sınıfı, iki farklı alt sınıf tarafından genişletilmiştir:

ZorunluDers ve SecmeliDers sınıfları, kalıtım yoluyla Ders sınıfından türetilmiş ve bu derslerin özelliklerine göre farklı davranışlar tanımlanmıştır.

🔹 Arayüz (Interface)

IRaporlanabilir adında bir arayüz tanımlanmış ve bu arayüzü uygulayan sınıflar, sistemde transkript yazdırma, not raporlama gibi görevleri üstlenmiştir.

Böylece, farklı sınıfların ortak davranışları bağımsız şekilde gerçekleştirmesi sağlanmıştır.

🔧 Modül Yapısı ve İşlevleri

📌 1. Öğrenci Kayıt Modülü

Yeni öğrencilerin sisteme kaydını sağlar.

Öğrencinin kimlik bilgileri alınarak Ogrenci nesnesi oluşturulur.

📌 2. Ders Kayıt Modülü

Öğrencilerin Zorunlu veya Seçmeli derslere kayıt olmasını sağlar.

Dersler, Dictionary<Ogrenci, List<Ders>> yapısında tutulur. Böylece her öğrencinin kayıtlı dersleri pratik bir şekilde izlenebilir.

📌 3. Not Girişi Modülü

Ders sorumluları, her öğrenci için sınav notlarını sisteme girebilir.

Notlar Not sınıfında tutulur ve ortalama hesaplamaları yapılır.

📌 4. Transkript Görüntüleme ve Yazdırma Modülü

Öğrencilerin aldıkları dersler ve notlar, transkript formatında console ekranına yazdırılır.

IRaporlanabilir arayüzü sayesinde bu işlem esnek ve modüler biçimde gerçekleştirilmiştir.



AYBERK ERDEM - Fırat Üniversitesi Bilgisayar Mühendisliği

MEHMET KAĞAN BAYRAK - Fırat Üniversitesi Bilgisayar Mühendisliği

