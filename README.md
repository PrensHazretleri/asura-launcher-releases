# Asura SMP Launcher

Asura SMP (`play.asurasmp.com`) için Minecraft launcher'ı.

**İndir:** [En son sürüm](https://github.com/PrensHazretleri/asura-launcher-releases/releases/latest) sayfasındaki `AsuraLauncher-Setup-….exe` dosyasını indirip kur. Sonraki sürümler kendiliğinden kurulur.

Windows ilk kurulumda "bilinmeyen yayıncı" uyarısı gösterebilir; "Ek bilgi" > "Yine de çalıştır" ile devam edebilirsin.

# Güncelleme Geçmişi

## 2.3.1 — 2026-11-13

- Yeni: Rust Edition'da B tuşundaki ifade çarkı artık dolu: Selam, Dans, Hop, Reverans, Zafer, Bravo, Robot ve Gel buraya. Dans ve Robot sen hareket edene kadar sürer. Çevrimdışı hesaplarda çalışır; ifadeyi yalnızca sen görürsün.

## 2.3.0 — 2026-11-13

- Yeni: Hesap kilidi. Profiller > anahtar düğmesinden hesabını kendi launcher'ına kilitleyebilirsin: şifreni bilen biri başka bir bilgisayardan ya da elle /login yazarak giremez. Yeni bir bilgisayarı hesabının bağlı olduğu Discord ile onaylarsın (en fazla 5 bilgisayar). Hesabın /esle ile Discord'a bağlı olmalı.
- Yeni: Son girişler. Aynı yerde hesabına son 10 girişi görürsün: ne zaman, launcher'la mı elle mi, bu bilgisayardan mı ve farklı bir internetten mi.
- Yeni: Seri ve etkinlik hatırlatıcısı. Bugünün hediyesini almadıysan ve serin bozulacaksa akşam bir kez, sunucu etkinliği başlamadan 10 dakika önce de bildirim gelir. Ayarlar > Bildirimler'den "Windows açılınca arka planda başlat"ı açarsan launcher saatin yanında sessizce bekler.
- Yeni: Arkadaşlar. Ana Sayfa'da arkadaşının adını ekle ya da "Şu an oyunda" listesinde yıldıza bas: arkadaşın oyuna girince haber verilir, kimin oyunda olduğunu da görürsün.
- Yeni: PvP kaynak paketleri. Modlar sayfasında Low Fire, Low Shield, küçük totem, PvP nişangahı ve PvP doku paketleri tek tıkla açılır; Rust Edition'da da çalışır.
- Yeni: Markette indirim olunca Ana Sayfa'da kalan süresiyle birlikte görünür ve bir kez bildirim gelir.
- Yeni: Bağlantı testi. Ayarlar > Bağlantı Testi: 15 saniyede sorunun senin internetinde mi yoksa sunucuya giden yolda mı olduğunu söyler; sonucu kopyalayıp Discord'a atabilirsin.
- Yeni: Kıyafet sayfası. Sol menüdeki tişört simgesinden her hesabının skinini ve pelerinini seçersin: skin dosyası yükle ya da başka hesabının skinini giy. Yüklediğin skin artık launcher'da da görünür.
- Kıyafet sayfasında karakterin 3B ve pelerini sırtında: kendi kendine döner, sürükleyerek çevirirsin, boşta dururken el sallar, etrafa bakar, zıplar, ara sıra dans eder ("Dans" düğmesiyle de dans ettirirsin). Karaktere tıklarsan hasar alır.
- Ayarlar artık ayrı bir pencerede açılıyor: Oyun, Java, Launcher, Bildirimler, Rust Edition, Sesli Sohbet, Bağlantı Testi ve Sorun Giderme diye kategorilere ayrıldı, arama kutusuyla istediğin ayarı bulursun.
- Sol menü artık yalnız simgelerle açılır: sol üstteki Asura logosuna basınca genişler, tekrar basınca daralır; launcher seçimini hatırlar.
- Yeni: Dans! Oyunda B tuşuna basınca emote çarkı açılır: el sallarsın, alkışlarsın, ters takla atarsın, dans edersin. Danslarını yalnızca launcher kullanan oyuncular görür. Modlar sayfasındaki Sosyal bölümünden (Emotecraft) kapatabilirsin.
- Yeni: Oyun çökünce "Güvenli modda aç". Oyun bir kez yalnızca gerekli modlarla açılır; böylece çökmeye bir modun mu sebep olduğunu anlarsın. Modların silinmez, sonraki açılışta hepsi geri gelir.

## 2.2.0 — 2026-11-12

- Rust Edition için 5 grafik ayarı: Ultra Performans, Performans, Normal, Kalite ve Ultra. Launcher'da Ayarlar > Rust Edition Grafik Ayarı'ndan seçersin, oyunu açınca uygulanır. Bizim testimizde Ultra Performans Ultra'nın yaklaşık 3,5 katı FPS verdi.
- Seçtiğin ayar yalnızca bir kez yazılır: sonra oyunda değiştirdiğin ayarlar sen yeni bir ayar seçene kadar kalır. Performans ayarlarının kapattığı VSync, FPS sınırı ve shader, başka bir ayara geçince geri gelir.
- "Bilgisayarıma göre ayarla" artık Rust Edition için de uygun grafik ayarını seçer.
- Rust Edition'daki AsuraSMP Ayarları sayfalarının hepsi artık Türkçe (PvP ve HUD, kontrolcü, modlar, ekstralar, HDR dahil).
- Ayarlar sayfasının bazen hiç açılmaması düzeltildi.

## 2.1.0 — 2026-11-12

- Bitdefender gibi bazı antivirüs programlarının Rust Edition'ı açtıktan sonra launcher'ı engellemesi düzeltildi: launcher artık arka planda PowerShell çalıştırmıyor. Launcher'ın açılmıyorsa launcher.asurasmp.com/indir adresinden yeniden kur.
- Rust Edition'da Asura açılış ekranı artık sunucuya bağlanıp dünya yüklenene kadar kalır ve Asura SMP'nin kaynak paketi "Evet / Hayır" sorusu olmadan gelir (2.0.0'ı ilk saatlerde indirenler için).

## 2.0.0 — 2026-11-12

- Asura Launcher 2.0: Rust Edition artık sesli sohbet, gruplar, Asura menüsü, otomatik giriş, günlük ödüller ve pelerinlerle geliyor.
- 1.21.4 launcher'ın sürüm listesinden kaldırıldı; neredeyse kimse oynamıyordu. 1.21.4 seçili olanlar 26.3 ile açılır. O sürümdeki dünyaların ve ekran görüntülerin silinmez, Galeri'de görünmeye devam eder.
- Launcher'dan girenler Asura SMP'nin kaynak paketini artık "Evet / Hayır" sorusu olmadan, doğrudan alır.
- Rust Edition'da ESC menüsünde yeni "Asura SMP" düğmesi: sesli sohbet, gruplar, pelerin seçimi (Kozmetikler), günlük ödül durumu ve Discord tek yerde. Oyunda seçtiğin pelerini launcher da hatırlar.
- Rust Edition açılırken artık "Horizon" yazısı yerine Asura SMP açılış ekranı görünür ve sunucuya bağlanıp dünya yüklenene kadar ekranda kalır; pencerenin adı ve simgesi de baştan Asura SMP.
- Yeni medya pelerinleri: YouTube, TikTok, Instagram ve Kick. Yalnızca medya rolündeki oyunculara açık, oyunda Kozmetikler'den seçilir.
- Yeni: Rust Edition'da sesli sohbet. Launcher mikrofonunu sunucuya taşır; yakındaki oyuncuları duyarsın, Fabric'te Simple Voice Chat kullananlar da seni duyar. Oyun açıkken launcher'ı kapatma.
- Bas-konuş tuşu varsayılan olarak Caps Lock (Simple Voice Chat'teki gibi). Oyunda V'ye basınca sesli sohbet ayarları açılır: ses seviyesi, bas-konuş / sesle açılma, eşik, mikrofon, mikrofonu kapat, sesi tamamen kapat.
- Tuşları kendin seçebilirsin: Ayarlar > Rust Edition Sesli Sohbet'te "Değiştir"e ya da oyundaki ayar ekranında "Tuşu değiştir"e basıp istediğin tuşa (fare yan tuşları dahil) bas.
- Tuşlar yalnızca oyun penceresi öndeyken ve sohbet kapalıyken çalışır; sohbete yazarken mikrofon açılmaz.
- Sunucunun kuralları Rust Edition'da da geçerli: sesli sohbet susturması ve /seskayit onayı olmadan konuşamazsın, ama diğerlerini duyarsın.
- Rust Edition artık Görev Yöneticisi'nde ve Discord'da "Horizon" yerine Asura SMP adı ve simgesiyle görünür.
- Rust Edition sesli sohbetinde gruplar: oyunda O'ya (ya da V ekranındaki "Grup"a) basınca gruba katılabilir, şifreli ya da şifresiz grup kurabilir, gruptan ayrılabilirsin. Gruptakiler birbirini her yerden duyar; Simple Voice Chat kullananlarla aynı gruplar.
- Rust Edition'da launcher artık sunucuya kendini tanıtıyor (sesli sohbet kapalıyken de): launcher'da kayıtlı şifrenle otomatik giriş yaparsın, günlük ödüllerini alırsın, launcher'da seçtiğin skin uygulanır ve pelerinini Fabric'te oynayanlar görür.
- OBS'de "Oyun Yakalama" kullanan yayıncılar için ses simgesi: Ayarlar > Rust Edition Sesli Sohbet'teki adresi OBS'ye "Tarayıcı" kaynağı olarak ekleyince simge yayında da görünür.

## 1.6.0 — 2026-11-10

- Yeni (deneysel): 26.3 Rust Edition. Minecraft 26.3'ün Rust ile yeniden yazılmış hali (Horizon); bizim testimizde yaklaşık 3 kat FPS. Sürüm listesinden "26.3 Rust Edition (deneysel)" seçip oynayabilirsin, varsayılan sürüm yine Fabric 26.3.
- RAM: Aynı bilgisayarda play.asurasmp.com'da, görüş mesafesi 12'de Görev Yöneticisi'ne göre normal 26.3 ~1,75 GB, Rust Edition ~0,78 GB kullandı (yaklaşık %55 daha az). Rust Edition dünya verisinin bir kısmını ekran kartı belleğinde tutuyor.
- İçinde hazır gelenler (Seçenekler > AsuraSMP Ayarları): Mouse Tweaks, envanter sıralama, Fullbright, dinamik ışık, otomatik yeniden bağlanma, akıcı sohbet, özel nişangah, FPS / koordinat / ping / tuş göstergeleri.
- İlk açılışta kendini kurar (1,5-2 dakika, diskte yaklaşık 1,5 GB) ve direkt play.asurasmp.com'a bağlanır.
- Rust Edition'da henüz otomatik giriş, ödüller, pelerin, sesli sohbet, Fabric modları, shader, zoom ve mini harita yok: /giris şifreni kendin yazarsın. Vulkan veya DirectX 12 destekleyen ekran kartı ister.

## 1.5.1 — 2026-11-04

- Yayıncı modu açıkken F3+B (hitbox) ve F3+G (chunk sınırları) artık çalışıyor; koordinatlar F3 ekranında yine gizli.
- F3+B veya F3+G açıkken Asura göstergeleri artık kaybolmuyor.
- 26.3'te sunucudan çıkınca oyunun çökmesi düzeltildi.

## 1.5.0 — 2026-11-03

- Yeni mod: Freelook. Sol Alt'ı basılı tutunca yürüdüğün yönü değiştirmeden etrafına bakabilirsin.
- Yeni mod: Mouse Tweaks. Envanterde fareyi sürükleyerek eşyaları hızlıca taşır, dağıtır ve toplarsın.
- İkisi de bütün sürümlerde kurulu gelir; istemezsen "Modlar" sayfasından kapatabilirsin.

## 1.4.1 — 2026-11-03

- 1.21 sürümü bazı modlar açıkken (ör. Effect Timer Plus) açılmıyordu, düzeltildi.

## 1.4.0 — 2026-11-03

- Yeni sürümler: Minecraft 26.3 ve 1.21 artık launcher'da. Sürüm listesinden seçip oynayabilirsin; diğer sürümler aynen duruyor.

## 1.3.0 — 2026-11-02

- Otomatik yeniden bağlanma: sunucu yeniden başlatıldığında ya da bağlantın koptuğunda oyun sunucu açılana kadar kendiliğinden yeniden bağlanmayı dener (en fazla 30 dakika). Ekrandaki düğmeyle iptal edebilirsin. "Bağlantıyı Kes" ile çıktığında, kick ya da ban yediğinde yeniden bağlanmaz.

## 1.2.4 — 2026-10-25

- 1.2.3'te launcher açılırken hata veriyordu, düzeltildi. 1.2.3'ü aldıysan launcher'ı launcher.asurasmp.com/indir adresinden indirip tekrar kur.
- Yeni grafik modu: Ultra Performans. Zayıf bilgisayarlar için en yüksek FPS: en kısa görüş mesafesi, tüm efektler kısık, VSync ve FPS sınırı kapalı. Oyunda Asura menüsünden seçebilirsin.

## 1.2.3 — 2026-10-25

- Yeni grafik modu: Ultra Performans. Zayıf bilgisayarlar için en yüksek FPS: en kısa görüş mesafesi, tüm efektler kısık, VSync ve FPS sınırı kapalı. Oyunda Asura menüsünden seçebilirsin.

## 1.2.2 — 2026-10-18

- Discord eşleme artık oyunda: sunucuda /esle yaz, çıkan kodu Discord sunucumuzda /esle ile gir. Launcher'daki "Discord bağla" düğmesi kaldırıldı.
- /esle ile bağlı hesaplarda launcher'daki "Şifremi unuttum" çalışır.

## 1.2.1 — 2026-10-17

- Xaero's Minimap mod listesinden kaldırıldı. Açık olanlarda bir sonraki OYNA'da kendiliğinden silinir.
- Launcher güncellemeleri artık çok daha hızlı iniyor.

## 1.2.0 — 2026-10-15

- Yeni ESC menüsü: ortada Asura logosu ve Oyuna Dön, Client Ayarları, Oyun Ayarları, Gelişimler, İstatistikler, Modlar, Bağlantıyı Kes; sağda karakterin ve Kozmetikler.
- Kozmetikler: pelerinini artık oyunun içinden seçebilirsin. Taktığın pelerini herkes anında görür, launcher da seçimini hatırlar. Seriyle açılan pelerinler serin yetene kadar kilitli görünür.
- Galeri: oyunda F2 ile çektiğin ekran görüntüleri launcher'daki yeni Galeri sekmesinde. Büyüt, tek tıkla kopyalayıp Discord'a yapıştır, klasörde göster ya da sil.
- Etkinlikler: ana sayfada sıradaki sunucu etkinliği geri sayımla görünür.
- Asura'nın yeni rengi kızıl: launcher ve oyun içi menüler yeni renklere büründü.
- Launcher artık geniş ekran açılıyor ve açılışta Asura SMP yazısı masaüstünde beliriyor.
- Ana sayfadaki ping artık doğru: oyunun sunucu listesinin gösterdiği değerle aynı.

## 1.1.0 — 2026-10-13

- Sohbeti açınca FPS, ping ve diğer göstergeler artık kaybolmuyor; yazarken de ekranda kalır.

## 1.0.0 — 2026-10-09

- Launcher girişi: sunucu şifreni launcher'a bir kez yaz, artık /login yazmadan gir. Şifren bilgisayarında şifrelenerek saklanır ve yalnızca Asura SMP sunucusuna gönderilir.
- Her hesap kendi şifresini saklar: şifresi kayıtlı olmayan hesapta "şifre gerekli" yazar. Birden fazla hesapla aynı anda 4 oyuna kadar açmaya devam edebilirsin.
- Şifren yanlışsa oyun bunu sana söyler ve her zamanki gibi /login ile girersin; doğrusunu Profiller sayfasındaki anahtar düğmesinden kaydedersin.
- Şifreni launcher'dan değiştir: Profiller sayfasındaki anahtar düğmesinden yeni şifreni yaz; sunucuya bir sonraki girişinde sunucudaki şifren de değişir, oyunda komut yazman gerekmez.
- Discord bağlama: Profiller sayfasındaki anahtar düğmesinden hesabını Discord'a bağla. Şifreni unutursan "Şifremi unuttum" ile launcher'dan yenisini belirlersin.
- Günlük hediye, giriş serisi ve seri pelerinleri artık yalnızca launcher girişi doğrulanan hesaplara verilir.
- Skin ve pelerin değişiklikleri yalnızca hesabın gerçek sahibi için geçerli olur: başkası senin adınla görünümünü değiştiremez.
- Launcher'sız oyuncular için bir şey değişmedi: /login ile girmeye devam.

## 0.7.2 — 2026-10-09

- Arayüzü Düzenle'de göstergeler artık kendiliğinden hizalanıyor: sürüklediğin kutu ekran kenarlarına, ortaya ve diğer kutulara yapışır, pembe çizgi nereye oturduğunu gösterir.
- Arayüzü Düzenle ekranında yalnızca açık olan göstergeler görünür.
- Giriş ekranı sadeleşti: daha anlaşılır yazılar ve geçersiz oyuncu adında anında uyarı.

## 0.7.1 — 2026-10-09

- Göstergeler ayrıldı: FPS, ping, koordinat, CPS, saat, yön ve efektler artık ayrı ayrı küçük kutular; her birini Arayüzü Düzenle ekranında tek tek taşıyabilirsin.
- Zırh göstergesi yenilendi: zırhların eşya resimleriyle dikey dizilir, yanında kalan dayanıklılık yazar ve azaldıkça sarıya, kırmızıya döner.
- Arayüzü Düzenle ekranı düzeltildi.
- Ayrı zırh göstergesi modu (uku's Armor HUD) kaldırıldı; yerini Asura Menü'deki Zırh Durumu aldı.

## 0.7.0 — 2026-10-09

- Asura Menü yenilendi: daha geniş, iki sütunlu yeni tasarım ve beş yeni gösterge: CPS, Zırh Durumu, Efektler, Saat ve Yön. Hepsi kapalı gelir, istediğini açarsın.
- Yayıncı Modu açıkken Asura Menü'deki Koordinat anahtarı kilitlenir.
- Yeni seçmeli mod: Xaero's Minimap (Modlar sayfasından açılır).
- Launcher'a yeni arka plan ve açılış animasyonu eklendi.

## 0.6.3 — 2026-10-09

- "Tam ekran başlat" açıkken oyunda F11 ile tam ekrandan çıkılamıyordu; düzeltildi.

## 0.6.2 — 2026-10-09

- Launcher'dan açılan Yayıncı Modu artık oyundaki Asura Menü'den o oturum için kapatılabiliyor; oyunu yeniden açınca tekrar açık gelir.
- Asura Menü'de "Ekran Görüntüleri" düğmesinin yazısı artık düğmeye sığıyor.

## 0.6.1 — 2026-10-09

- Bazı oyuncuların sırtında görünen "Update Cosmetica To V2" yazılı sarı pelerin düzeltildi.

## 0.6.0 — 2026-10-09

- Kendi skinini yükle: Profiller sayfasından bilgisayarındaki skin dosyasını seç; sunucuya girdiğinde herkes onu görür. Orijinal hesap gerekmez.
- Seriyle kazanılan pelerinler: Alev 7 günlük, Ay Yıldız 15 günlük, yeni Efsane pelerini 30 günlük giriş serisiyle açılır. Bir kez kazandığın pelerin serin bozulsa da kalır.
- Asura Menü'ye yeni araçlar: Ekran Görüntüleri klasörü, Discord ve Oy Ver düğmeleri.
- Oy ver: ana sayfada "Bugün oy vermedin" hatırlatıcısı. Düğmeye basınca oy sayfası açılır ve kullanıcı adın kopyalanır; siteye yapıştırman yeter.
- Launcher'dan Yayıncı Modu: Ayarlar'dan aç, oyun her açılışta koordinatlar gizli başlasın. Açıkken koordinat gösteren modlar (BetterF3) kurulmaz.
- Bilgisayarına göre ayarla: launcher RAM'ine ve ekran kartına bakıp ayrılacak RAM'i ve grafik modunu seçer. Yeni kurulumlarda kendiliğinden yapılır; Ayarlar'daki düğmeyle istediğin zaman tekrarlayabilirsin.
- Sunucu durumu artık yanlışlıkla "çevrimdışı" görünmüyor.
- Birden fazla hesabın varsa giriş serisi kutusu artık seçili hesabın serisini gösterir.
- Skin seçimi sadeleşti: isim yazmak yerine kayıtlı hesaplarından birinin skinini listeden seçersin. Skini olmayan isimlerde önizleme artık bunu açıkça söylüyor.

## 0.5.2 — 2026-10-09

- Freelook modu kaldırıldı.

## 0.5.0 — 2026-10-09

- Giriş serisi: launcher ile her gün gir, ödülün büyüsün. 7. günden itibaren Oy Kasası, 15. günden itibaren Titan Kasası, 25. günden itibaren Ametist Kasası anahtarı; 15. ve 30. günde büyük kristal ikramiyesi. Serin ana sayfada görünür.
- Pelerinler: Profiller sayfasındaki tişört düğmesinden sekiz pelerinden birini seç. Pelerinini Asura Launcher ile oynayan herkes görür.
- Skin seçici: aynı yerden beğendiğin bir oyuncunun adını yaz, önizle ve skinini kullan.
- Yeni Modlar sayfası: modları gruplar halinde gör, tek tıkla aç kapat. Hazır profiller: Sade, PvP, Yapı, Yayıncı.
- Yeni seçmeli modlar: AppleSkin, Shulker Box Tooltip, zırh göstergesi, efekt süreleri, BetterF3, dinamik ışıklar, çerçevesiz tam ekran, Freelook, Litematica ve Mod Menu.
- Yakınlaştırma artık WI Zoom ile: C tuşuna bas, fare tekerleğiyle yakınlığı ayarla.
- ESC menüsü yenilendi: "Asura Menü" düğmesi grafik modlarını, göstergeleri ve Yayıncı Modu'nu tek bir panelde toplar.
- Ana sayfada şu an oyunda olan oyuncuları görürsün.
- Kristal göstergesi kaldırıldı; kristal sayın zaten TAB listesinde.

## 0.4.0 — 2026-10-09

- Oyunun ana menüsüne "Asura SMP'ye Bağlan" düğmesi eklendi: tek tıkla sunucuya girersin.
- Günlük launcher hediyenin durumu ana sayfada: bugün aldın mı, seni bekliyor mu görürsün.
- Yeni Ayarlar sayfası: çözünürlük, tam ekran, Java seçimi ve bilgisayarına göre RAM önerisi.
- "Dosyaları onar": oyun açılmıyorsa Ayarlar > Sorun Giderme'den tek tıkla dosyaları doğrulat.
- Modları sen seç: shader, yakınlaştırma, tam parlaklık ve skin modlarını Ayarlar'dan açıp kapat; hazır shader paketini indir; "Mod klasörünü aç" ile kendi Fabric modunu ekle.
- Arayüzü Düzenle: ESC menüsünden göstergeleri (FPS, koordinat, kristal, tuşlar) sürükleyip ekranda istediğin yere taşı.
- Kristal göstergesi: ESC menüsünden açarsan kristal sayın ekranın köşesinde görünür.
- Discord düğmesi: ana sayfadan ve çökme penceresinden tek tıkla Discord sunucumuza gel.
- Yayın başlayınca masaüstü bildirimi (Ayarlar'dan kapatılabilir).
- İndirme sırasında kalan boyut ve tahmini süre gösteriliyor; profilinde skininin yüzü görünüyor.
- Launcher artık kendi logosuyla geliyor ve OYNA düğmesi her zaman ekranda.

## 0.3.2 — 2026-10-08

- Oyun açıkken launcher'ı kapatmak artık oyunu kapatmıyor: launcher saatin yanındaki simgelere iner, son oyun kapanınca kendisi de kapanır.
- Discord profilinde artık "AsuraSMP oynuyor" görünüyor (Discord açıkken, oyun süresince).
- Launcher ile giren oyuncular sunucuda duyuruluyor ve günlük hediye alıyor: 1 Para Kasası Anahtarı, 1 Event Kasası Anahtarı ve 25 kristal.

## 0.3.1 — 2026-10-08

- Sunucu artık Asura Launcher ile giren oyuncuları tanıyor. Launcher'a özel hediyeler için duyuruları takip et.

## 0.3.0 — 2026-10-08

- Yeni Minecraft sürümleri: artık 1.21.4'ün yanında 1.21.11 ve 26.2 ile de oynayabilirsin. Sürümü OYNA düğmesinin yanındaki "Kurulum" kutusundan seçersin.
- Yeni bir sürüme ilk geçişte tuş, ses ve görüntü ayarların 1.21.4'teki ayarlarından kopyalanır.
- ESC menüsündeki Asura düğmeleri (Performans / Orta / Kalite, Sesleri Sıfırla, FPS / Ping, Tuşlar, Yayıncı Modu) üç sürümde de var.
- Giriş ekranı sadeleşti: orijinal hesabın olsa da kullanıcı adını yazıp girmen yeterli, skinin kendiliğinden gelir.
- Bir mod seçtiğin sürüme henüz çıkmamışsa oyun artık hata vermek yerine o mod olmadan açılır.
- Güncelleme geçmişi artık launcher'ın ana sayfasında görünüyor.

## 0.2.1 — 2026-10-08

- Aynı anda birden fazla hesap: farklı profillerle birden çok oyun açabilirsin (en fazla 4). Hesabı OYNA'nın yanındaki "Hesap" kutusundan seç.
- Açık oyunlar ana sayfada listelenir ve tek tek kapatılabilir.
- Koordinatlar artık sen açmadıkça ekranda görünmez. FPS / Ping kutusu da varsayılan olarak kapalı gelir; ikisi ESC menüsünden açılır.
- Güncellemeler zorunlu ve otomatik: yeni sürüm çıkınca launcher kendisi indirir, kurar ve yeniden açılır.

## 0.2.0 — 2026-10-08

- Asura SMP kurulumu: Fabric 1.21.4 ve gerekli modlar tek tıkla kurulur.
- Performans modları: Sodium, Lithium ve FerriteCore.
- Sesli sohbet: Simple Voice Chat kurulu gelir.
- ESC menüsüne grafik modları (Performans / Orta / Kalite) ve Sesleri Sıfırla düğmesi eklendi.
- C tuşuyla yakınlaştırma, shader desteği (Iris), tam parlaklık ve çevrimdışı hesaplar için skin desteği.
- play.asurasmp.com çok oyunculu listesinde en üstte; istersen oyun açılınca doğrudan sunucuya bağlanır.
- Yeni arayüz: canlı sunucu durumu, oyuncu sayısı ve Kick yayını açıkken "CANLI" rozeti.
- Oyun çökerse sebebini anlatan ve logu tek tıkla paylaşmanı sağlayan pencere.
- Otomatik güncelleme.
