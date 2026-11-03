# Oyun Kitabı: Yapay Zeka Destekli Vatandaş + Avukat Platformu

Genel çerçevelerin bir hukuk teknolojisi ürününe uygulanmış hali. Ürün ayrıntıları için önce
`../sablonlar/urun-profili.md`'yi oku; buradakiler varsayılan hipotezlerdir.

## 1. Temel gerçek: iki ayrı ürün, iki ayrı pazarlama

| | Vatandaş (B2C) | Avukat (B2B / profesyonel) |
|---|---|---|
| Satın alma tetikleyicisi | Ani, duygusal bir olay (tebligat, işten çıkarılma, kira zammı, boşanma, kaza) | Verimlilik, zaman, müvekkil memnuniyeti, rekabet |
| İhtiyaç sıklığı | Düzensiz, nadir | Günlük |
| Ana kaygı | "Doğru mu söylüyor? Hakkımı kaybeder miyim?" | "Doğru mu? Gizlilik? Meslek kurallarına uygun mu?" |
| Kanal | Google arama, kısa video, WhatsApp ile kulaktan kulağa | LinkedIn, barolar/etkinlikler, meslektaş tavsiyesi, doğrudan satış |
| Gelir modeli adayı | Ücretsiz ilk soru + kredi paketi / belge başı ücret | Aylık/yıllık abonelik (kullanıcı başı), büro paketi |
| Kuzey Yıldızı | Faydalı bulunan yanıt / tamamlanan belge | Haftalık aktif büro / kullanım saati |

**Strateji önerisi:** İki tarafı aynı anda büyütmeye çalışma. Hangisi daha hızlı para ve öğrenme
getiriyorsa onu "çekirdek" yap, diğerini ona hizmet edecek şekilde konumla.
- Avukat tarafı genellikle **daha öngörülebilir gelir** ve daha düşük hukuki risk sunar.
- Vatandaş tarafı **daha büyük kitle ve marka bilinirliği** sunar ama nadir kullanım ve tutundurma sorunu vardır.

## 2. İki taraflı pazar yeri ve "soğuk başlangıç" (Andrew Chen)
Eğer vatandaşları avukatlarla buluşturuyorsan:
- **Zor taraf** (genellikle kaliteli avukatlar) önce. Onlar için tek başına değerli bir araç sun ("araç için gel, ağ için kal" — come for the tool, stay for the network).
- **Atomik ağ:** Türkiye'nin tamamı yerine tek bir şehir + tek bir hukuk alanı (ör. İstanbul'da kira/iş hukuku) ile başla, orada yoğunluk kur.
- **Reklam yasağı uyarısı:** Eşleştirme modeli, ücretlendirme ve avukat gösterim biçimi md. 55 açısından en riskli kısım. Komisyon yerine avukata sabit yazılım aboneliği, vatandaşa tarafsız (sıralamasız, puansız) dizin/baro yönlendirmesi gibi modelleri bir avukatla değerlendir (dosya 10).

## 3. Konumlandırma taslakları

**Vatandaş:**
> Hukuki bir sorunla karşılaştığında, Google'da kaybolmak ya da hemen pahalı bir danışmanlık almak
> yerine, haklarını dakikalar içinde sade bir dille öğren ve bir avukata hazırlıklı git.
Kategori: "Hak rehberi / hukuki bilgi asistanı" (danışmanlık değil).

**Avukat:**
> Türk hukukuna göre eğitilmiş, kaynak gösteren yapay zeka ile araştırma ve taslak süresini kısaltan,
> müvekkil verisini KVKK'ya uygun saklayan dijital büro asistanı.
Kategori: "Hukuk büroları için yapay zeka asistanı".

## 4. Güven inşası (her iki taraf için 1 numaralı dönüşüm kolu)
- **Kaynak gösterme:** Her yanıtta kanun maddesi ve emsal karar referansı, tıklanabilir.
- **Avukat danışma kurulu:** Gerçek isimlerle, içerik kalitesini denetleyen avukatlar (kendi reklamları yapılmadan, ölçülü sunum).
- **Şeffaflık sayfası:** Model nasıl çalışır, sınırları neler, veriler nerede saklanır, hata bildirimi.
- **Güvenlik/KVKK rozetleri yerine somut bilgi:** Veri Türkiye'de mi, şifreleme, saklama süresi, eğitimde kullanılıyor mu.
- **Gerçek kullanım verisi:** "Bu ay X soru yanıtlandı" (doğrulanabilir).

## 5. Vatandaş tarafı büyüme motoru

1. **SEO + araçlar:** "Kira artış hesaplama", "kıdem tazminatı hesaplama", "tebligat süreleri", "dilekçe örnekleri". Her araç/sayfa sonunda "Durumunu sor" CTA'sı. (dosya 06)
2. **Kısa video "haftalık hak":** Gündemle bağlantılı (yılbaşı zamları, kira dönemi, yeni kanun). Yorumdan DM'e kontrol listesi. (dosya 05)
3. **Paylaşılabilir çıktı:** Kullanıcının sonuç özetini (kişisel veri olmadan) paylaşabileceği kart → STEPPS "Public".
4. **Mevsimsellik takvimi:** Ocak (zamlar, kira), Haziran-Eylül (kira sözleşmeleri, taşınma), seçim/afet/kanun değişikliği dönemleri, Kasım-Aralık (Black Friday tüketici hakları).
5. **Ortaklıklar:** Emlak siteleri, işçi/tüketici dernekleri, belediyelerin hukuki danışma birimleri, üniversite hukuk klinikleri.
6. **Avukata yönlendirme:** Sorun karmaşıksa nazikçe "bir avukata danış" — güven yaratır; yönlendirme biçimini mevzuata uygun kur.

## 6. Avukat tarafı büyüme motoru

1. **Kurucu satışı:** İlk 20-50 büroyu birebir demo ile kazan; her görüşme bir Mom Test görüşmesidir.
2. **LinkedIn:** Kurucu hesabı + avukat kullanıcı hikâyeleri ("Dilekçe taslağı 3 saatten 40 dakikaya"); avukatın kendi reklamını yapmayan, ürün odaklı vaka formatı.
3. **Eğitim pazarlaması:** "Avukatlar için yapay zeka" webinarları, baro eğitim merkezleri (CMK, staj eğitimleri), hukuk fakülteleri — öğrenciler yarının müşterisi.
4. **Kurucu müşteri programı:** İlk 50 büroya ömür boyu indirim karşılığında geri bildirim ve referans (gerçek kontenjan = etik kıtlık).
5. **Ürün içi viral:** Müvekkile gönderilen belgeler/portal linkleri ürünü görünür kılar.
6. **İtiraz yönetimi:** Gizlilik (veri nerede?), doğruluk (halüsinasyon), meslek kuralları, fiyat. Her biri için tek sayfalık yanıt hazırla.

## 7. İçerik sütunları (kurucu kişisel hesabı)

| Sütun | Vatandaşa | Avukata |
|---|---|---|
| Eğitici | "Bilmen gereken haklar" | "Hukuk bürosunda yapay zeka iş akışları" |
| Yolculuk | Hukuk teknolojisi girişimi kurmak | Ürün geliştirme, avukatlardan öğrenilenler |
| Kanıt | Anonim kullanıcı hikâyeleri | Büro vaka çalışmaları |
| Görüş | Adalete erişim, hukuk dilinin sadeleşmesi | Yapay zeka ve mesleğin geleceği, etik |

Kurucunun siber güvenlik geçmişi güçlü bir farklılaştırıcıdır: **"güvenlik öncelikli hukuk yapay zekası"**
mesajı hem avukatların gizlilik kaygısına hem KVKK'ya doğrudan cevap verir.

## 8. İlk 90 gün planı (varsayılan)

| Hafta | Odak | Çıktı |
|---|---|---|
| 1-2 | Araştırma | Her iki taraftan 10'ar Mom Test görüşmesi, PMF anketi (mevcut kullanıcılara), hukuki model kontrolü (avukatla) |
| 3-4 | Konumlandırma | Seçilen çekirdek taraf için konumlandırma cümlesi, landing page yenileme, teklif kanvası |
| 5-8 | Kanal testi | 1 ana kanal (ör. kısa video veya LinkedIn) haftada 4-5 içerik + 1 lead magnet + otomasyon; SEO için 10 soru sayfası / 1 hesaplayıcı |
| 9-12 | Optimizasyon | Haftalık rapor, en zayıf huni adımı için deneyler, kazanan formatları çoğalt, ilk fiyat testi |

Başarı kriteri: 90 gün sonunda **tek bir kanaldan öngörülebilir kayıt akışı** ve aktivasyon/tutundurma
eğrisinin iyileşmesi. Takipçi sayısı ikincil metrik.
