# Müteahhit Eşleştirme

Kat karşılığı ve kentsel dönüşüm yerlerini müteahhitlerle eşleştiren sayfa.

Sayfa: https://ozgurtufekci-tzx.github.io/muteahhit-eslestirme/

- Sayfa yalnızca kullanıcı adı ve şifreyle açılır; kayıtlar şifreli saklanır.
- **Admin** her şeyi yapar: müteahhit ekler/siler, JSON yükler, portföyü yönetir, "Kullanıcılar" sekmesinden kullanıcı ekler/siler.
- **Kullanıcı** yalnızca müteahhitlerin taleplerini (aradığı bölgeler, m² aralığı, çalışma şekli, not) girer.

Dosyalar:
- `data/muteahhit.enc`: müteahhitler ve portföydeki yerler (şifreli)
- `data/ek-bilgiler.enc`: JSON'dan gelen ek bilgiler (şifreli, sayfada gösterilmez)
- `data/kullanicilar.json`: kullanıcılar; kayıt anahtarı ve şifre çözme anahtarı burada şifreli durur, her kullanıcı kendi şifresiyle açar

İlk kurulum: sayfada "Giriş yap"a basıp admin hesabını oluşturun (bir kez GitHub anahtarı istenir).
