# iLaw Hukuk — tanıtım sayfası ve gizlilik politikası

Bu klasör herkese açık web sitesinin kaynağıdır. Yayın: ayrı ve herkese açık `mukreminyuksel/ilaw-site`
deposu, GitHub Pages (`main` dalı, kök) → `https://mukreminyuksel.github.io/ilaw-site/`.
Asıl depo (`ilaw`) özel olduğu için site ayrı depoda yayımlanır; değişiklik burada yapılır, sonra o depoya
kopyalanır (docs/SUNUCU.md §0a/9).

| Dosya | Görev |
| --- | --- |
| `index.html` | Ana sayfa (Google giriş ekranının "uygulama ana sayfası" bağlantısı) |
| `gizlilik.html` | Gizlilik Politikası, ön sürüm (v0.12.1, yayın 2 Kasım 2026; kullanıcı kararı: hukukçu incelemesi mağaza yayınından önce, SUNUCU §0b/9). `#silme`: hesap silme |
| `kosullar.html` | Kullanım Koşulları, ön sürüm (v0.12.1, yayın 2 Kasım 2026; aynı karar). Uygulamada koşul sürümü `TERMS_VERSION` = yayın tarihi |
| `icon.png`, `favicon.png` | Uygulama simgesinden küçültülmüş |
| `indir.html` | Test sürümünü kurma, hesabı kaydetme, ana sürüme geçiş (uygulamadaki "Yeni sürümü indir" buraya açılır) |
| `surum.json` | Uygulamanın okuduğu uzaktan sürüm ayarı: `latest` (son sürüm), `minVersionCode` (bundan eski sürüm kapanır), `downloadUrl`, `testEndsAt`, `notice`. Her yeni sürümde `latest` güncellenir (docs/SUNUCU.md §3f) |
| `.nojekyll` | GitHub Pages dosyaları olduğu gibi sunar |

Gizlilik metni uygulamanın gerçek veri akışını anlatır (docs/SUNUCU.md §3c–§3e, docs/MIMARI.md §7a). Veri
akışı değişirse (yeni veri, yeni paylaşım) bu metin de güncellenir.
