# Şahan Pro (yönetim paneli): LinkedIn paylaşımı

Görseller (bu sırayla): `sahan-pro_01.png` → `sahan-pro_02.png` → `sahan-pro_03.png` → `sahan-pro_04.png`

Not: Görsellerdeki firma adı, telefon, adres ve vergi bilgileri maskelendi. Tüm müşteri ve tutar verisi uydurmadır.
Herkese açık web sitesi ayrı bir paylaşım oldu: `../sahan-site/sahan-site_linkedin.md`.

---

Geçtiğimiz aylarda bir düğün fotoğrafçısı için web sitesi yapmıştım. Sonra asıl ihtiyacın sitenin arkasında olduğu ortaya çıktı. Rezervasyonlar, ödemeler, sözleşmeler ve fotoğraf seçimleri hep farklı yerlerde tutuluyordu. Bir çiftin ne kadar ödemesi kaldığını öğrenmek bile vakit alıyordu.

Bunun için bir yönetim paneli geliştirdim.

Panelde her iş tek bir listede duruyor ve hangi aşamada olduğu (sözleşme, ödeme, fotoğraf seçimi, düzenleme) bir bakışta görülüyor. Ana ekranda o ayın geliri, tahsil edilen ve bekleyen ödemeler çıkıyor. Teklif ve sözleşmeyi panelde doldurup PDF olarak alabiliyorlar.

Müşteri tarafını da düşündüm. Çiftler telefonlarına gelen kodla giriş yapıyor, sözleşmeyi onaylıyor, fotoğraf ve müzik seçimlerini kendileri yapıyor. Çekimden bir gün önce de otomatik SMS hatırlatması gidiyor. Fotoğrafçının ve videocunun kendi iş listeleri var. Yönetici girişi de iki adımlı doğrulamayla korunuyor.

Arka tarafta Python (FastAPI), PostgreSQL ve Redis kullandım, PDF'leri Playwright ile ürettim.

Siz işinizi takip etmek için kaç farklı uygulama kullanıyorsunuz?

#webgeliştirme #python #fastapi #kobi #yazılım
