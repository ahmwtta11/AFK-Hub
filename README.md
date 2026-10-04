# AFK Hub Kullanım Kılavuzu

## Uygulamayı açma

GitHub Releases bölümünden uygulamanın `.exe` dosyasını indirip çalıştırın. Sunucu seçme ekranı açılır.

## Uzak panele bağlanma

1. Panelin web adresini girin. Minecraft oyun sunucusunun adresini değil, AFK Hub panel adresini kullanın.
2. Sağdaki oka basın.
3. Panel giriş ekranı açılınca sunucu için tanımlı kullanıcı adı ve şifreyle giriş yapın.

Örnek adresler:

```text
https://panel.example.com
http://vds/vpsipadresi
```

Port belirtilmeyen `http://` adreslerinde uygulama varsayılan olarak `3000` portunu da dener. HTTPS adreslerinde sunucunun kullandığı portu yazın.

## Yerel sunucuyu kullanma

Yerel kullanım için bilgisayarda Node.js ve npm kurulu olmalıdır.

1. Sunucu seçme ekranında **Yerel Sunucu** anahtarını açın.
2. İlk kurulumda dosyaların kopyalanıp bağımlılıkların yüklenmesini bekleyin.
3. Durum alanında sunucunun çalıştığı görününce sağdaki oka basın.
4. Giriş ekranında yerel sunucu hesabıyla oturum açın.

Yeni kurulumun varsayılan girişi `admin` / `admin` şeklindedir. İlk girişten sonra **Şifre Değiştir** bölümünden değiştirin. Daha önce yerel sunucu kullanıldıysa mevcut hesap bilgileri geçerlidir.

## Paneli kullanma

- **Yeni Bot** düğmesinden Minecraft sunucu adresi, port ve bot hesabı bilgilerini girip botu oluşturun.
- Envanterde bir slota tıklayarak eşya seçin. Eşyaları sürükleyerek taşıyabilir, çift tıklayarak bırakma onayını açabilirsiniz.
- Sunucu seçme ekranına dönmek için `Ctrl+Shift+S` kısayolunu kullanın.
- Yerel sunucuyu kapatmak için sunucu seçme ekranında **Yerel Sunucu** anahtarını kapatın.
