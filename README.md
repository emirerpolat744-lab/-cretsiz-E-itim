# öğren. — Herkes İçin Eğitim (iPhone / iOS)

Bu paket iPhone ekranlarına göre tasarlanmış, Türkçe bir web sitesi içerir. HTML, CSS ve JavaScript ile hazırlanmıştır; APK gerekmez.

## Hızlı deneme
`index.html` dosyasını bilgisayarda bir tarayıcıda açabilirsiniz. iPhone'da dosyayı doğrudan açmak bazı iOS sürümlerinde sınırlı olabilir; herkese açık bir URL için siteyi HTTPS destekleyen bir statik hosting hizmetine yükleyin.

## iPhone'da ana ekrana ekleme
1. Siteyi HTTPS bağlantısıyla Safari'de açın.
2. Paylaş simgesine dokunun.
3. **Ana Ekrana Ekle** seçeneğini seçin. Gerekirse "Web Uygulaması Olarak Aç" seçeneğini etkinleştirin.
4. **Ekle**'ye dokunun. Artık simgesinden açabilirsiniz.

## GitHub Pages ile yayınlama
1. GitHub'da yeni bir depo (repository) oluşturun.
2. ZIP içindeki dosyaları çıkarıp `index.html`, `style.css`, `script.js`, `manifest.webmanifest`, `icon.svg` ve `sw.js` dosyalarını depo köküne yükleyin.
3. Depoda **Settings → Pages** bölümüne girin.
4. **Deploy from a branch** seçin, `main` ve `/(root)` seçip kaydedin.
5. GitHub'ın verdiği HTTPS adresini iPhone'da Safari ile açın. Yayınlanması birkaç dakika sürebilir.

## Özellikler
- iPhone odaklı responsive tasarım ve alt gezinme çubuğu
- Ders arama ve kategori filtreleri
- Ders bilgi pencereleri ve tamamlandı işaretleme
- İlerleme bilgisi aynı tarayıcıda saklanır
- HTTPS üzerinden yayınlandığında çevrimdışı önbellek için service worker
- Ana ekrana eklenmeye yönelik web app manifest ve simge

Not: Bu bir ön yüz eğitim prototipidir. Hesap sistemi, çevrim içi veritabanı veya gerçek ders sunucusu içermez. Service worker ve ana ekrana ekleme özellikleri için HTTPS üzerinden yayınlamak önerilir. Google Fonts internet bağlantısı gerektirir; bağlantı yoksa sistem yazı tipleri kullanılır.
