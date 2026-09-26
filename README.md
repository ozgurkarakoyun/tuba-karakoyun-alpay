# Uzm. Dr. Tuba Karakoyun Alpay
Türkçe, mobil uyumlu nöroloji uzmanı web sitesi. İletişim yalnızca Instagram üzerinden sunulur.

## Çalıştırma
Node.js 22 veya üstü ile `npm start`. Varsayılan port 3000; Railway'in PORT değişkeni desteklenir. Harici bağımlılık yoktur.

## Yayına alma
Bu klasörün içeriğini yeni bir GitHub deposunun köküne yükleyin. Railway'de GitHub deposunu bağlayın. Dockerfile otomatik kullanılır. Sağlık kontrolü `/health`, HTTP portu Railway tarafından PORT ortam değişkeniyle atanır. Railway Networking bölümünden domain oluşturun. Sonradan özel alan adı bağlanabilir.

## Düzenleme
İçerik: public/index.html. Görünüm: public/styles.css. Mobil menü: public/app.js. Portre: public/assets/doctor-cutout.webp.
Yönetim paneli, izleme çerezi, form veya hasta verisi toplama bulunmaz. Biyografi kullanıcı tarafından verilen bilgilerle hazırlanmıştır; mezuniyet tarihi, deneyim yılı veya başarı oranı eklenmemiştir. Fotoğraf kullanıcı tarafından sağlanmış ve beyaz önlük eklenerek düzenlenmiştir. Tıbbi bilgilendirme kaynakları sayfada yer alır.
