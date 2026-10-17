# Müteahhit Eşleştirme

Kat karşılığı ve kentsel dönüşüm yerlerini müteahhitlerle eşleştiren sayfa.

Sayfa: https://ozgurtufekci-tzx.github.io/muteahhit-eslestirme/

- Liste girişsiz görüntülenir.
- **Admin** her şeyi yapar: müteahhit ekler/siler, JSON yükler, portföyü yönetir, "Kullanıcılar" sekmesinden kullanıcı ekler/siler.
- **Kullanıcı** yalnızca müteahhitlerin taleplerini (aradığı bölgeler, m² aralığı, çalışma şekli, not) girer.

Dosyalar:
- `data/muteahhit.json`: müteahhitler ve portföydeki yerler
- `data/ek-bilgiler.json`: JSON'dan gelen ek bilgiler (sayfada gösterilmez)
- `data/kullanicilar.json`: kullanıcılar; kayıt için gereken GitHub anahtarı burada şifreli durur, her kullanıcı kendi şifresiyle açar

İlk kurulum: sayfada "Giriş yap"a basıp admin hesabını oluşturun (bir kez GitHub anahtarı istenir).
