Proje Adı
Hesap Makinesi
Proje Açıklaması
Bu Python programı, temel matematiksel işlemleri (toplama,
çıkarma, çarpma ve bölme) gerçekleştiren bir hesap makinesi
işlevi görür. Kullanıcıya, matematiksel işlemler seçme ve iki sayı
girme olanağı sağlar. Program ayrıca kullanıcıya çıkış yapma
seçeneği sunar.
Özellikler
• Toplama, çıkarma, çarpma ve bölme işlemlerini gerçekleştirme.
Kullanıcıdan iki sayı alma.
Hatalı girişleri işleme ve kullanıcıyı bilgilendirme.
Sıfıra bölme hatasını yönetme.
Programdan çıkış yapma seçeneği.
Program çalıştığında aşağıdaki seçenekleri sunar:
Yapmak istediğiniz işlemi seçin:
1. Toplama
2. Çıkarma
3.Çarpma
4.Bölme
5.Çıkış
İşlem seçimini yaparak (1/2/3/4/5) uygun
seçeneği girin.3. Sayı Girişi:
Seçilen işleme göre iki sayı girilmesi istenir:
Birinci sayıyı girin: <say11>
İkinci sayıyı girin: <say12>
Sayılar doğru formatta girilmelidir (örn. 10, 3.5).
4. Sonuç:
İşlem sonucunu ekranda görürsünüz:
Sonuç: <sonuç>Fonksiyonlar
1. toplama(a, b):
Açıklama: İki sayının toplamını hesaplar.
Parametreler:
`a` (float): İlk sayı.
`b` (float): İkinci sayı.
Dönüş Değeri: Toplam (float).
2. cikarma(a, b):
Açıklama: İki sayı arasındaki farkı hesaplar.
Parametreler:
`a` (float): İlk sayı.
`b` (float): İkinci sayı.
Dönüş Değeri: Fark (float).
3. carpma (a, b):
Açıklama: İki sayının çarpımını hesaplar.
Parametreler:
`a` (float): İlk sayı.
`b` (float): İkinci sayı.
Dönüş Değeri: Çarpım (float).
4. bolme(a, b):
Açıklama: İki sayının bölümünü hesaplar. Bölme sırasında sıfıra
bölme hatasını kontrol eder.
Parametreler:
`a` (float): Bölünen sayı.
`b` (float): Bölen sayı.
Dönüş Değeri: Bölüm (float) veya hata mesajı (string).5. hesap_makinesi():
Açıklama: Kullanıcıdan işlem ve sayılar alır,
sonucu hesaplar ve ekrana yazdırır.
Programdan çıkış yapma seçeneği sunar.
İşleyiş:
Kullanıcıdan işlem seçimini alır.
Seçime göre uygun matematiksel fonksiyonu çağırır.
Sayı girişini alır ve sonucu hesaplar.
• Hatalı girişlerde kullanıcıyı bilgilendirir.
Çıkış seçeneği seçilirse, programdan çıkar.
mesaji
Hata Yönetimi
Geçersiz Sayı Girişi: Sayı formatı hatalıysa kullanıcıya bilgi verir
ve tekrar giriş yapmasını ister.
Sıfıra Bölme: Bölen sıfır olduğunda, hata mesajı gösterir ve
işlem gerçekleştirilmez.


Proje Açıklaması

Bu proje, öğrenci kayıtlarını yönetmek için bir veritabanı tasarımı ve uygulaması sunmaktadır. Veritabanı, öğrenci bilgilerini, ders bilgilerini ve ders kayıtlarını saklamak için tasarlanmıştır. Proje, veritabanı şemasını, SQL betiklerini ve örnek sorguları içerir.


Veritabanı Şeması: Tablolar, sütunlar ve tablolar arasındaki ilişkiler hakkında bilgi.

SQL Betikleri: Veritabanını oluşturmak, tablo oluşturmak, veri eklemek, güncellemek ve silmek için kullanılan SQL betikleri.

Örnek Sorgular: Veri ekleme, güncelleme, silme ve alma işlemleri için SQL sorguları.
