# BTK Akademi Video Otomatik Oynatma ve Ders Geçme Eklentisi

**BTK Akademi dersleri hızlı bitirme**, videoları arka planda kesintisiz oynatma ve bir sonraki derse otomatik geçiş yapma amacıyla hazırlanmış **Tampermonkey (Userscript)** otomasyonudur.

> **Not:** Projede ufak hatalar bulunabilir; geliştirmek veya hata bildirmek için Issue/PR açabilirsiniz.

## BTK Akademi Otomatik Video İzleme Nasıl Kurulur?

1. Tarayıcınıza **Tampermonkey** eklentisini kurun ve bu repodaki JavaScript kodunu yeni betik olarak ekleyin.
2. Chrome'un arka plan sekme ve zamanlayıcı kısıtlamalarını devre dışı bırakmak için **Win + R** tuşlarına basıp aşağıdaki komutu çalıştırın:

```cmd
chrome.exe --user-data-dir="C:\temp\btk_oto" --disable-backgrounding-occluded-windows --disable-renderer-backgrounding --disable-background-timer-throttling --autoplay-policy=no-user-gesture-required
```

https://github.com/user-attachments/assets/969ec711-a651-4638-97c2-eba08586aff0



