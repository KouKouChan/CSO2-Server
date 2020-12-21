## Counter-Strike Online 2 Sunucusu 

[![Build status](https://ci.appveyor.com/api/projects/status/a4pj1il9li5s08k5?svg=true)](https://ci.appveyor.com/project/KouKouChan/cso2-server)
[![](https://img.shields.io/badge/license-MIT-green)](./LICENSE)
[![](https://img.shields.io/badge/version-v0.5.0-blue)](https://github.com/KouKouChan/CSO2-Server/releases)

***Oyun İçin Yapılan Son Güncellemeyi İndirmek İçin [21.12.2020_CSO2_21_12_2020_Update_2GB_or_high.rar](https://drive.google.com/file/d/1tOYUGa3vOxgJoHPrYA7BoejwAeQ-N8sg/view?usp=sharing) İyi Oyunlar.***

### 0x01 Açıklama

Counter-Strike Online 2 Sunucusu

***L-leite tarafından [cso2-master-server](https://github.com/L-Leite/cso2-master-server) temel alınmıştır.***


***Tüm Lokasyon Dosylaları Olur！3. Bölüme Bakın.***

### 0x02 Oyunun Özellik Planları

    1. Temel Oynanış √
    2. Yeniden Düzenle...

### 0x03 Lokasyonunuzu Ayarlayın

```
1. CSO2-Server\locales\ klasöründe en-us.ini gibi bir yerelleştirme dosyası oluşturun
2. Lokasyonunuzun dosyasını ekleyin veya düzenleyin, zh-cn.ini'yi örnek olarak görebilirisiniz
3. Server.conf dosyasını düzenleyin ve LocaleFile'ı dosya adınıza ayarlayın
```

### 0x04 Oynanış

    1. Kore versiyonu olan bir oyun istemciniz olmalıdır.
    2. L-leite'in github sayfasından bir başlatıcı indirin.
    3. En son oyun sunucusu dosyasını ( https://github.com/KouKouChan/CSO2-Server/releases ) adresinden indirin
    4. Oyun sunucusunu başlatın ve oyununuzu başlatmak için Başlatma dosyasını kullanın.
    5. İyi Eğlenceler

**Dikkat**!

- Kaydı etkinleştirmek istiyorsanız, server.conf dosyasını değiştirmeli ve EnableRegister'ı 1'e ayarlamalı ve e-posta smtp sunucunuzu ve e-posta kodunuzu ayarlamalısınız. Daha sonra tarayıcınızla localhost:1314'ü açabilirsiniz.

### 0x05 Yapı İnşası

    1. Herhangi Bir Dizinde Klasör Açın
    2. Oyunu inşa yapısını derlemek için 'go build' Komutunu girin
    3. Çalıştır Ve Tamamlandı!

### 0x06 Aşağıdaki Gereksinimler

    Go 1.15.3
    Bağlantı Noktaları:30001-TCP、30002-UDP

***Bir LAN veya İnternet Sunucusu kurmak istiyorsanız, lütfen güvenlik duvarı bağlantı noktasını açın.***

### 0x07 Ekran Görüntüleri

![Image](./photos/main.png)

![Image](./photos/intro.png)

![Image](./photos/channel.png)

![Image](./photos/ingame.jpg)

![Image](./photos/result.jpg)
