# Kasa: LinkedIn paylaşımı

Görseller (bu sırayla): `kasa_01.png` → `kasa_03.png` → `kasa_02.png` → `kasa_04.png`
(Ekstre önizlemesi `kasa_03.png` en güçlü özellik olduğu için 2. sıraya alındı.)

Not: Hesap adları, banka adı, işlemler ve tutarlar uydurmadır. Ekstre ekranındaki dosya, deneme için hazırlanmış sahte bir CSV'dir.

---

Geçtiğimiz aylarda bir işletme için gelir-gider uygulaması geliştirdim.

İşletme "bu ay ne kazandık?" sorusunu cevaplamak için banka ekstrelerini satır satır Excel'e geçiriyordu. Üstelik aynı ekstre iki kez girilince gelir iki katı görünüyor, kredi kartı ödemesi gider sanılıyordu.

Uygulamada banka ya da kredi kartı ekstresini (PDF, Excel veya CSV) yüklemek yetiyor. Sistem satırları okuyor ve akaryakıt, kira, fatura, kargo gibi kategorileri kendisi atıyor. Kullanıcı bir kategoriyi düzeltirse bunu öğreniyor, sonraki ekstrelerde aynı kuralı uyguluyor. Daha önce yüklenmiş satırları tanıyıp atlıyor. Hesaplar arası transferleri de rapora karıştırmıyor.

Bunların yanında gider analizi, abonelik takibi, ay sonu kontrol ekranı ve çalışan ödemeleri var. Kimin neyi değiştirdiği de kayıt altında tutuluyor.

Python (FastAPI), PostgreSQL, pdfplumber ve openpyxl kullandım.

Siz işletmenizin gelirini ve giderini nasıl takip ediyorsunuz?

#python #fastapi #muhasebe #kobi #yazılım
