# WorldForge | Latest Stable-Based Development Package

*A browser-based fantasy tabletop role-playing campaign and worldbuilding tool.*

WorldForge helps Game Masters organize a campaign's world, lore, characters, locations, maps, sessions, and relationships in one browser-based workspace.

## Features

- **Campaign workspace:** access the campaign dashboard and related worldbuilding tools.
- **World encyclopedia:** create and organize lore entries.
- **GM notes and player preview:** mark encyclopedia entries for GM or player visibility and preview the player-facing interface.
- **Linked entries:** connect encyclopedia records to each other.
- **Typed relationships:** label connections with types such as ally, family, enemy, suspicion, secret connection, political, trade, and shared history.
- **Relationship graph:** inspect connections between encyclopedia entries and supported linked campaign objects.
- **Map workshop:** continue working with the stable map workshop from the v2.2.0 baseline.
- **Single-file app:** the main application is a standalone HTML file that can be opened in a modern browser.

## Download and run

1. Extract this ZIP archive.
2. Open `WorldForge-v0.3.3-Iliski-Turleri.html` in a modern browser.
3. Use the app to manage your campaign. Keep a backup of the HTML file and any browser-local data you rely on.

Some online or shared-campaign features may depend on external service configuration and should not be assumed to work as a fully hosted multiplayer service out of the box.

## Version and testing notes

This package combines the known stable v2.2.0 application base with the later v0.3.0–v0.3.3 encyclopedia enhancements. The experimental v2.3.x embedded-atlas builds are intentionally excluded because they had image-cropping/rendering problems in testing.

The HTML JavaScript passed syntax checks, the key v0.3.3 feature markers are present, and the ZIP archive was integrity-checked. A full end-to-end browser regression test has **not** been completed, so test the application with a copy of your campaign data before relying on it in a live session.

## Security note

The GM/player preview and visibility filter in this standalone browser app are **client-side interface behavior**, not server-side authorization. Do not use them as a security boundary for confidential information in a shared or public deployment. A real multi-user deployment needs server-side authorization and appropriate database access policies. Never put Supabase service-role keys or other private secrets in the client HTML or a public repository.

## License

No license has been specified. Until a license is added, reuse and redistribution are not automatically granted.

---

# WorldForge | Türkçe

*Tarayıcı tabanlı fantastik masaüstü rol yapma oyunu, kampanya ve dünya oluşturma aracı.*

WorldForge; Oyun Yöneticilerinin (GM) kampanya dünyasını, hikâye bilgilerini, karakterleri, konumları, haritaları, oturumları ve ilişkileri tek bir tarayıcı çalışma alanında düzenlemesine yardımcı olur.

## Özellikler

- **Kampanya çalışma alanı:** Kampanya paneli ve dünyayı oluşturma araçlarına erişim.
- **Evren ansiklopedisi:** Hikâye ve evren kayıtları oluşturma, düzenleme ve düzenli tutma.
- **GM notları ve oyuncu ön izlemesi:** Ansiklopedi kayıtlarını GM'ye özel veya oyunculara açık olarak işaretleme ve oyuncuların göreceği arayüzü ön izleme.
- **Bağlantılı kayıtlar:** Ansiklopedi kayıtlarını birbirine bağlama.
- **İlişki türleri:** Müttefiklik, aile, düşmanlık, şüphe, gizli bağ, siyaset, ticaret ve ortak geçmiş gibi bağlantı türleri belirleme.
- **İlişki grafiği:** Ansiklopedi kayıtları ve desteklenen bağlantılı kampanya öğeleri arasındaki ilişkileri inceleme.
- **Harita atölyesi:** v2.2.0 kararlı tabanındaki harita atölyesini kullanmaya devam etme.
- **Tek dosyalı uygulama:** Ana uygulamanın modern bir tarayıcıda açılabilen bağımsız bir HTML dosyası olması.

## İndir ve çalıştır

1. Bu ZIP arşivini çıkarın.
2. `WorldForge-v0.3.3-Iliski-Turleri.html` dosyasını güncel bir tarayıcıda açın.
3. Kampanyanızı uygulama içinde yönetin. HTML dosyasının ve güvendiğiniz tarayıcı yerelindeki verilerin yedeğini alın.

Bazı çevrim içi veya ortak kampanya özellikleri harici servis yapılandırması gerektirebilir. Uygulamanın hiçbir ek ayar olmadan tamamen barındırılan çok oyunculu bir hizmet gibi çalıştığı varsayılmamalıdır.

## Sürüm ve test notları

Bu paket, bilinen kararlı v2.2.0 uygulama tabanını v0.3.0–v0.3.3 serisinde eklenen ansiklopedi geliştirmeleriyle birleştirir. Görsel kırpma/görüntüleme sorunları yaşanan deneysel v2.3.x gömülü atlas sürümleri bu pakete dahil edilmemiştir.

HTML içindeki JavaScript sözdizimi denetiminden geçti, v0.3.3 özelliklerine ait temel işaretler doğrulandı ve ZIP arşivinin bütünlüğü kontrol edildi. Ancak tarayıcıda baştan sona tam regresyon testi **tamamlanmış değildir**. Canlı oturumda kullanmadan önce kampanya verilerinizin bir kopyasıyla test edin.

## Güvenlik notu

Bağımsız tarayıcı uygulamasındaki GM/oyuncu ön izlemesi ve görünürlük filtresi **istemci tarafında çalışan arayüz davranışıdır**; sunucu taraflı yetkilendirme değildir. Paylaşılan veya herkese açık bir dağıtımda gizli bilgileri korumak için güvenlik sınırı olarak kullanılmamalıdır. Gerçek çok kullanıcılı bir dağıtım için sunucu taraflı yetkilendirme ve uygun veritabanı erişim politikaları gerekir. Supabase service-role anahtarlarını veya başka gizli bilgileri istemci HTML dosyasına ya da herkese açık depoya kesinlikle koymayın.

## Lisans

Henüz bir lisans belirtilmemiştir. Lisans eklenene kadar yeniden kullanım ve yeniden dağıtım için otomatik izin verilmiş sayılmaz.
