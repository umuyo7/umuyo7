# Kasa: LinkedIn paylaşımı

Görseller (bu sırayla): `kasa_01.png` → `kasa_03.png` → `kasa_02.png` → `kasa_04.png`
(Ekstre önizlemesi `kasa_03.png` en güçlü özellik olduğu için 2. sıraya alındı.)

Not: Hesap adları, banka adı, işlemler ve tutarlar uydurmadır. Ekstre ekranındaki dosya, deneme için hazırlanmış sahte bir CSV'dir.

---

Bir işletmenin "bu ay ne kazandık?" sorusunu cevaplamak için banka ekstrelerini satır satır Excel'e kopyalaması gerekiyordu.

Sorun sadece zaman değildi. Aynı ekstre iki kez girilince gelir iki katı görünüyordu. Kredi kartı ödemesi gider sanılıyor, hesaplar arası transferler rapora karışıyordu.

Bunun için bir gelir-gider uygulaması geliştirdim:

📄 Banka ve kredi kartı ekstresini (PDF, Excel, CSV) yüklüyorsunuz, sistem satırları okuyup önizleme gösteriyor
🏷 Kategoriler otomatik atanıyor (akaryakıt, kira, fatura, kargo...). Kullanıcının düzeltmeleri sonraki yüklemelerde kural olarak kullanılıyor
🔁 Daha önce kaydedilmiş satırlar parmak iziyle tanınıp atlanıyor
✅ Hareketler onay sırasından geçiyor, iç transferler rapora girmiyor
📊 Genel bakış, gider analizi, abonelik takibi ve ay sonu sağlama ekranı
👥 Çalışan ödemeleri, sanal fonlar ve kimin neyi değiştirdiğini gösteren denetim kaydı

Teknolojiler: Python, FastAPI, PostgreSQL, SQLAlchemy, Jinja2, pdfplumber, openpyxl.

Siz işletmenizin gelir-giderini nasıl takip ediyorsunuz?

#python #fastapi #muhasebe #kobi #yazılım
