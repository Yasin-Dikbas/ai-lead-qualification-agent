# Silent Demo + Captions Script: AI Lead Qualification Agent

Ses yok. Sadece ekran kaydı + üstte kısa metin kutuları (caption/overlay). ~75-90 saniye.

## Kayıt (Loom, sessiz)

1. Loom'u aç, **Screen Only** seç (mikrofon kapalı / muted).
2. Aşağıdaki akışı, aralarında gereksiz bekleme olmadan kaydet. Fare hareketlerin yavaş ve net olsun (viewer'ın okuyacak zamanı olsun).
3. Bitince **Stop**, videoyu indir (mp4).

### Sahne sahne ne yapacaksın (ses yok, sadece aksiyon)

| Süre | Ekranda ne yapıyorsun |
|---|---|
| 0:00-0:08 | Boş n8n canvas'ı 2 saniye göster, sonra yavaşça soldan sağa pan/scroll yap (Webhook → AI → Sheets → If → Gmail/Telegram node'ları sırayla görünsün) |
| 0:08-0:15 | PowerShell'e geç, test komutunu çalıştır (`Invoke-RestMethod ...`) |
| 0:15-0:35 | n8n canvas'ına dön, node'ların sırayla yeşile dönmesini izlet (execution'ı aç, canlı akışı göster) |
| 0:35-0:50 | Google Sheets sekmesine geç, yeni satırı (Score, Label, Summary dahil) göster |
| 0:50-1:05 | Telegram sekmesine geç, gelen "🔥 New HOT lead" bildirimini göster |
| 1:05-1:20 | Gmail sekmesine geç, gelen kişiselleştirilmiş takip mailini aç ve göster |
| 1:20-1:30 | n8n canvas'ına son bir kez dön, genel akışı 2 saniye göster, bitir |

## Caption / Overlay metinleri (post-production'da ekleyeceğin yazılar)

Her satırı, yukarıdaki zaman aralığına denk gelecek şekilde ekranın alt veya üst kısmına ekle. Kısa ve büyük puntolu olsun, 1-2 saniyede okunabilmeli.

| Zaman | Caption metni |
|---|---|
| 0:00 | **AI Lead Qualification Agent** |
| 0:03 | Most businesses lose leads because nobody answers fast. |
| 0:08 | A new lead comes in through a webhook... |
| 0:15 | ...an AI scores it instantly (0-100, hot/warm/cold) |
| 0:35 | ...saved automatically to a CRM record |
| 0:50 | Hot leads trigger an instant sales alert |
| 1:05 | ...and a personalized follow-up email — not a generic auto-reply |
| 1:20 | Demo build — adaptable to your CRM & tools (HubSpot, Slack, WhatsApp...) |
| 1:26 | Message me on Upwork to scope this for your business |

## Post-production: Clipchamp ile caption ekleme (Windows'ta hazır, ücretsiz)

1. Başlat menüsünden **Clipchamp**'i aç (Windows 11'de yüklü gelir, yoksa Microsoft Store'dan ücretsiz indir).
2. **Import media** ile indirdiğin Loom mp4'ünü içeri al, timeline'a sürükle.
3. Sol menüden **Text** sekmesine tıkla, basit bir şablon seç (örn. "Lower Third" veya "Simple Text"), timeline'da ilgili zamana sürükle.
4. Metin kutusuna yukarıdaki caption'lardan ilgilisini yaz, süresini (1.5-3 saniye) timeline üzerinde kısalt/uzat.
5. Her caption için 3-4 adımı tekrarla.
6. Sağ üstten **Export** → **1080p** ile mp4 olarak kaydet.

## Son adım: bitmiş videoyu Loom'a yükle (link almak için)

1. Clipchamp'tan çıkan mp4'ü loom.com'da **"Upload a video"** (yeni kayıt değil, mevcut dosya yükleme) seçeneğiyle yükle.
2. Loom sana paylaşılabilir bir link verecek — bu linki `README.md`'deki **Work with me** bölümüne ve Upwork portfolyonuza ekleyeceğiz.
