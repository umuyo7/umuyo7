# Bereket Sofram: LinkedIn paylaşımı

Görseller (bu sırayla): `bereket-sofram_01.png` → `bereket-sofram_02.png` → `bereket-sofram_03.png` → `bereket-sofram_04.png`

Not: Görsellerde işletme adı "Lokanta" olarak maskelendi. Menü, masa, adisyon, firma ve çalışan verileri uydurmadır.

Dikkat: Brief'te "PHP" yazıyordu ama güncel kod FastAPI (Python) ile yazılmış. Catering tarafı eski PHP sisteminin MariaDB veritabanını kullanmaya devam ediyor. Metin koddaki gerçek duruma göre yazıldı.

---

Aynı mutfaktan hem restoran salonuna hem de her gün onlarca firmaya yemek çıkıyorsa, işi kâğıt adisyon ve deftere bırakmak çok zor.

Birlikte çalıştığım işletme hem lokanta hem catering hizmeti veriyor. Masalar, paket siparişler, firmalara giden günlük yemekler ve tahsilatlar ayrı defterlerde tutuluyordu. Ay sonunda "hangi firma ne kadar borçlu?" sorusunun cevabını çıkarmak ciddi zaman alıyordu.

Bu iki işi tek bir sistemde topladım:

🍽 Restoran (POS):
• Masa planı, adisyon açma, masa taşıma, birleştirme ve bölme
• Dokunmatik kasa ekranı: nakit, kart, yemek kartı ve veresiye ile parçalı ödeme
• Mutfak fişi, vardiya açma/kapama ve gün sonu raporu
• Telefon, Trendyol Yemek ve Yemeksepeti paket siparişleri
• Rol ve yetki sistemi (garson, kasiyer, yönetici)
• Saatlik satış, ödeme yöntemi ve ürün bazında raporlar

🚚 Catering:
• Firma bazında günlük yemek ve mesai yemeği girişi
• Tahsilat, açık borç ve toplu PDF ekstre
• Gider, çalışan ve maaş takibi

Teknolojiler: Python, FastAPI, PostgreSQL, MariaDB, SQLAlchemy, Alembic, Docker.

Restoran işletenler: adisyonda en çok hangi adım vakit kaybettiriyor?

#webgeliştirme #python #fastapi #restoran #kobi
