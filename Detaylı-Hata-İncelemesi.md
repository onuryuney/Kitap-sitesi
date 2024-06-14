## Detaylı Hata İncelemesi

Her bir senaryoda karşılaşılabilecek olası hatalar ve bu hataların incelenmesi:

# 1. Ana Sayfa Görünümü
 Hata: Sayfa yavaş yükleniyor veya bazı öğeler eksik.
 İnceleme: Tarayıcı konsolunda hata olup olmadığını kontrol edin. Ağ trafiğini
izleyin ve yavaş yüklenen veya yüklenemeyen kaynakları tespit edin.

# 2. Kitap Listesi
 Hata: Kitap görselleri veya bilgileri eksik.
 İnceleme: Eksik öğelerin kaynaklarını kontrol edin. API çağrılarında sorun
olup olmadığını araştırın.

# 3. Kitap Detayları
 Hata: Detay sayfası doğru yüklenmiyor veya bilgiler eksik.

 İnceleme: Detay sayfasının doğru API çağrıları yapıp yapmadığını ve
yanıtların doğru olup olmadığını kontrol edin.

# 4. Kullanıcı Girişi

 Hata: Giriş yapılamıyor veya sistem çöküyor.
 İnceleme: Kullanıcı giriş API çağrılarını ve sunucu yanıtlarını kontrol edin.
Hata mesajlarını ve logları inceleyin.

# 5. Geçersiz Giriş Denemesi
 
 Hata: Yanlış bilgilerle giriş yapılabiliyor.
 İnceleme: Giriş doğrulama mekanizmalarını ve hatalı girişlerin nasıl
işlendiğini kontrol edin.

# 6. Kitap Ekleme (Kullanıcı Girişli)

 Hata: Kitap favorilere eklenemiyor.
 İnceleme: Kitap ekleme işleminin API çağrılarında hata olup olmadığını ve
kullanıcı veritabanına doğru eklenip eklenmediğini kontrol edin.

# 7. Kitap Ekleme (Kullanıcı Girişsiz)

 Hata: Giriş yapmadan kitap eklenebiliyor.
 İnceleme: Kullanıcı doğrulama ve yetkilendirme mekanizmalarını kontrol edin.


 ![kitap 1](https://github.com/onuryuney/Kitap-sitesi/assets/118278996/0affe2b8-ffde-4ff5-942d-e0515719e2ae)

![kitap 2](https://github.com/onuryuney/Kitap-sitesi/assets/118278996/326265c9-2bff-41b3-8dbb-ea29c334a53d)
