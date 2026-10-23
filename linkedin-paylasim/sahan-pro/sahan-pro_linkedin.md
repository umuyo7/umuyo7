# Şahan Pro (yönetim paneli): LinkedIn paylaşımı

Görseller (bu sırayla): `sahan-pro_01.png` → `sahan-pro_02.png` → `sahan-pro_03.png` → `sahan-pro_04.png`

Not: Görsellerdeki firma adı, telefon, adres ve vergi bilgileri maskelendi. Tüm müşteri ve tutar verisi uydurmadır.
Herkese açık web sitesi ayrı bir paylaşım oldu: `../sahan-site/sahan-site_linkedin.md` (bir hafta önce paylaşılacak).

---

Geçen hafta bir fotoğraf stüdyosu için yaptığım web sitesini paylaşmıştım. Bu hafta sitenin arkasında çalışan yönetim panelini anlatmak istiyorum.

Stüdyoda rezervasyonlar, ödemeler, sözleşmeler ve fotoğraf seçimleri farklı yerlerde duruyordu. Hangi çiftin hangi aşamada olduğu, kimin ne kadar ödemesinin kaldığı kolayca görülemiyordu.

Panelde neler var:
• Aylık gelir, tahsilat ve bekleyen ödemeleri gösteren özet ekranı
• Her işin durumunu (sözleşme, ödeme, fotoğraf seçimi, düzenleme) takip eden iş listesi
• Teklif ve sözleşme PDF'i hazırlayan, canlı önizlemeli belge oluşturucu
• Paket satış dağılımı ve aylık ciro raporları
• Çekimden önce otomatik SMS hatırlatmaları
• SMS koduyla giriş yapılan müşteri portalı: çift sözleşmesini onaylıyor, fotoğraf ve müzik seçimini buradan yapıyor
• Fotoğrafçı ve videocu için ayrı iş listeleri, yönetici girişinde iki adımlı doğrulama

Teknolojiler: Python, FastAPI, PostgreSQL, Redis, Jinja2, Playwright (PDF), Google Takvim entegrasyonu.

Sizce küçük işletmeler için en çok zaman kaybettiren iş hangisi: ödeme takibi mi, randevu yönetimi mi?

#webgeliştirme #python #fastapi #kobi #yazılım
