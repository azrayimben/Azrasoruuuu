# Azra'nın Soru Çözüm Günlüğü

## Dosyalar
- `sorular.html`: soru günlüğü, istatistikler ve günlük notlar.
- `manifest.webmanifest`: uygulama adı, ikonlar ve ana ekran başlatma ayarları.
- `sw.js`: uygulama kabuğu önbelleği; Supabase kişisel verileri önbelleğe alınmaz.
- `icons/`: uygulama simgeleri (PNG ve SVG).

## Çalıştırma / kısayol
PWA kurulum istemi için siteyi HTTPS üzerinden yayınlamalısın (ör. kendi hosting'in). HTML dosyasını doğrudan dosya yöneticisinden açmak, gerçek uygulama yükleme istemini genellikle sağlamaz. Chrome Android'de siteyi açıp `Uygulamayı Yükle` veya `Menü > Ana ekrana ekle` seçeneğini kullan.

## Supabase
Bu sürüm sağladığın Project URL ve publishable key'i kullanır. Tarayıcıda yalnızca publishable key bulunmalı; `service_role`/secret key ekleme. `question_entries` ve `daily_notes` tabloları ile kullanıcıya göre RLS politikaları önceden kurulmuş olmalı.

## Önemli kapsam notu
Bu arşivde, bu konuşmada kodu sağlanan `sorular.html` yer alır. `denemeler.html`, `index.html` veya ayrı `goruntule.html` dosyalarının kaynak kodu bu konuşmada verilmediği için bunlar arşive dahil değildir. İstenirse kaynakları ayrıca eklenerek aynı projeye entegre edilebilir.
