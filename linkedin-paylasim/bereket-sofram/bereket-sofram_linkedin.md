# Bereket Sofram: LinkedIn paylaşımı

Görseller (bu sırayla): `bereket-sofram_01.png` → `bereket-sofram_02.png` → `bereket-sofram_03.png` → `bereket-sofram_04.png`

Not: Görsellerde işletme adı "Lokanta" olarak maskelendi. Menü, masa, adisyon, firma ve çalışan verileri uydurmadır.

Dikkat: Brief'te "PHP" yazıyordu ama güncel kod FastAPI (Python) ile yazılmış. Catering tarafı eski PHP sisteminin MariaDB veritabanını kullanmaya devam ediyor. Metin koddaki gerçek duruma göre yazıldı.

---

Geçtiğimiz aylarda hem lokanta hem catering hizmeti veren bir işletme için yönetim sistemi geliştirdim.

İşletmede masalar, paket siparişler, firmalara giden günlük yemekler ve tahsilatlar ayrı ayrı tutuluyordu. Ay sonunda "hangi firma ne kadar borçlu?" sorusunun cevabını çıkarmak ciddi zaman alıyordu.

Restoran tarafında masa planı ve adisyon sistemi var. Masalar taşınabiliyor, birleştirilip bölünebiliyor. Kasa ekranını dokunmatik ekrana göre tasarladım. Nakit, kart, yemek kartı ve veresiye ile parçalı ödeme alınabiliyor. Mutfak fişi, vardiya ve gün sonu raporu da sistemde. Telefon, Trendyol Yemek ve Yemeksepeti siparişleri aynı yere düşüyor. Garson, kasiyer ve yöneticinin yetkileri ayrı.

Catering tarafında her firmanın günlük yemek sayısı giriliyor. Tahsilatlar ve açık borçlar takip ediliyor, ay sonunda ekstreler toplu PDF olarak alınıyor. Giderler, çalışanlar ve maaşlar da buradan yönetiliyor.

Python (FastAPI), PostgreSQL ve MariaDB kullandım. Sistem Docker üzerinde çalışıyor.

Restoran işletenlere sorayım: sizce en çok vakit hangi adımda kaybediliyor?

#webgeliştirme #python #fastapi #restoran #kobi
