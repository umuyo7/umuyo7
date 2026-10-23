# Şahan Pro: LinkedIn paylaşımı

Görseller (bu sırayla): `sahan-pro_01.png` → `sahan-pro_02.png` → `sahan-pro_03.png` → `sahan-pro_04.png`

Not: Görsellerdeki firma adı, telefon, adres ve vergi bilgileri maskelendi. Tüm müşteri ve tutar verisi uydurmadır, fotoğraflar yer tutucudur.

---

Bir fotoğraf stüdyosunun asıl işi fotoğraf çekmek. Ama günün büyük kısmı WhatsApp mesajları, Excel tabloları ve "kaporayı yatırdınız mı?" sorularıyla geçiyordu.

Bir düğün fotoğrafçısında rezervasyonlar, ödemeler, sözleşmeler ve fotoğraf seçimleri farklı yerlerde duruyordu. Hangi çiftin hangi aşamada olduğu kolayca görülemiyordu.

Bunun için iki parçalı bir sistem geliştirdim:

🌐 Herkese açık site: paketler, çekim konseptleri, blog ve rezervasyon formu. İçerikleri stüdyo bir CMS üzerinden kendisi güncelliyor.

🛠 Yönetim paneli:
• Aylık gelir, tahsilat ve bekleyen ödemeleri gösteren özet ekranı
• Her işin durumunu (sözleşme, ödeme, seçim, düzenleme) takip eden iş listesi
• Teklif ve sözleşme PDF'i hazırlayan belge oluşturucu
• Çekimden önce otomatik SMS hatırlatmaları
• SMS koduyla giriş yapılan müşteri portalı: çift sözleşmesini onaylıyor, fotoğraf ve müzik seçimini buradan yapıyor
• Fotoğrafçı ve videocu için ayrı iş listeleri

Teknolojiler: Python, FastAPI, PostgreSQL, Redis, Jinja2, Strapi CMS, Playwright (PDF), Google Takvim.

Sizce küçük işletmeler için en çok zaman kaybettiren iş hangisi: ödeme takibi mi, randevu yönetimi mi?

#webgeliştirme #python #fastapi #kobi #yazılım
