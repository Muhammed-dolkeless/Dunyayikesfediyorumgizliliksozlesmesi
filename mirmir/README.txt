MIRMIR GİZLİLİK POLİTİKASINI GITHUB PAGES İLE YAYINLAMA

Yayınlamadan önce index.html içindeki [DEVELOPER_NAME] ve [CONTACT_EMAIL]
alanlarını gerçek bilgilerle değiştirin.

1. GitHub'da yalnız gizlilik politikası için herkese açık bir depo oluşturun
   (örnek: mirmir-gizlilik). privacy_policy/index.html dosyasını bu yeni deponun
   köküne index.html adıyla yükleyin.

   Uygulama projesini, android/key.properties dosyasını, keystore dosyalarını,
   API anahtarlarını veya başka gizli bilgileri bu depoya yüklemeyin.

2. GitHub deposunda Settings > Pages bölümünü açın. Build and deployment altında
   Source olarak "Deploy from a branch", dal olarak "main" ve klasör olarak
   "/ (root)" seçip Save düğmesine basın.

3. Yayın tamamlanınca adres genellikle şu biçimde olur:
   https://KULLANICI_ADI.github.io/DEPO_ADI/

   Adresi gizli pencerede açarak sayfanın giriş yapmadan görüntülendiğini kontrol
   edin. Çalışan HTTPS adresini Google Play Console > Gizlilik Politikası alanına
   yapıştırın.

Politikayı zaten güvenli ve herkese açık olan bir projenin privacy_policy
klasöründen yayımlarsanız adres genellikle şu biçimdedir:
https://KULLANICI_ADI.github.io/DEPO_ADI/privacy_policy/

GitHub Pages belgeleri:
https://docs.github.com/pages/getting-started-with-github-pages/creating-a-github-pages-site

