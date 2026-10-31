# GitHub ile jar derleme (bilgisayara bir şey kurmadan)

1. github.com'da ücretsiz hesap aç / giriş yap.
2. Sağ üstte "+" > "New repository" de. İsim: WildClaim. Private seçebilirsin. "Create repository" de.
3. Açılan sayfada "uploading an existing file" bağlantısına tıkla.
4. Bu klasörün İÇİNDEKİLERİ (pom.xml, src, .github, .gitignore ...) sürükleyip bırak.
   Önemli: ".github" klasörü de yüklenmeli. Gizli klasör görünmüyorsa dosya gezgininde "gizli öğeleri göster" aç.
5. Altta "Commit changes" de.
6. Üstte "Actions" sekmesine gir. "Jar Derle" çalışmaya başlar (1-3 dk). Yeşil tik çıkınca tıkla.
7. Sayfanın altındaki "Artifacts" bölümünden "WildClaim-jar" dosyasını indir. Zip içinden WildClaim-1.0.0.jar çıkar.
8. Jar'ı sunucunun plugins klasörüne at ve sunucuyu yeniden başlat.

Kırmızı çarpı çıkarsa: Actions > hatalı çalıştırma > "derle" adımına tıkla, hata metnini Claude'a yapıştır.
