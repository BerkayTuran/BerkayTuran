# Büyüme ve Metrikler

## 1. Dört Uyum (Brian Balfour)
Büyüme tek bir hile değil, dört şeyin uyumudur:
- **Pazar – Ürün:** Ürün, gerçek bir kitlenin gerçek sorununu çözüyor mu?
- **Ürün – Kanal:** Ürün, seçilen kanala uygun mu? (Düşük fiyatlı B2C ürünü saha satışıyla satılmaz.)
- **Kanal – Model:** Kanal maliyeti, gelir modeliyle uyumlu mu? (Düşük ARPU → düşük CAC kanalları: SEO, viral, içerik.)
- **Model – Pazar:** Pazar büyüklüğü × fiyat hedef geliri taşıyor mu?

## 2. Core Four ve 100 Kuralı (Hormozi, *$100M Leads*)

| | Birebir | Bire-çok |
|---|---|---|
| **Seni tanıyanlar (sıcak)** | Sıcak erişim: tanıdıklara DM/arama | İçerik paylaşımı |
| **Tanımayanlar (soğuk)** | Soğuk erişim: e-posta, LinkedIn mesajı | Ücretli reklam |

**100 Kuralı:** 100 gün boyunca her gün 100 birim "talep üretme" işi yap (100 erişim mesajı, ya da 100 dakika içerik, ya da 100 TL reklam). Tutarlı hacim, taktik zekâsından önce gelir.

Ek kaldıraçlar: müşteri tavsiyesi, çalışanlar, ortaklar/affiliate, etkileyiciler.

## 3. AARRR (Korsan metrikleri)

| Aşama | Soru | Örnek metrik |
|---|---|---|
| **Acquisition** (Edinim) | Nereden geliyorlar? | Kanal bazında ziyaret, kayıt, CAC |
| **Activation** (Aktivasyon) | İlk değeri yaşadılar mı? | İlk 24 saatte ilk soruyu soran kayıt % |
| **Retention** (Tutundurma) | Geri geliyorlar mı? | 1/4/12. hafta kohort tutundurma, aylık churn |
| **Referral** (Tavsiye) | Başkasına anlatıyorlar mı? | Davet oranı, viral katsayı (K), NPS |
| **Revenue** (Gelir) | Para ödüyorlar mı? | Dönüşüm %, ARPU, MRR, LTV |

**Önce aktivasyon ve tutundurma.** Sızdıran kovaya su (trafik) dökmek para yakmaktır.

## 4. Kuzey Yıldızı Metriği
Müşterinin aldığı değeri en iyi temsil eden tek metrik. Gelir değil, gelirin öncü göstergesi.
- Vatandaş tarafı: "Haftalık çözülmüş/yanıtlanmış hukuki soru sayısı" veya "faydalı bulunan yanıt sayısı"
- Avukat tarafı: "Haftalık aktif hukuk bürosu" veya "platform üzerinden yönetilen dosya sayısı"
- Pazar yeri: "Başarılı vatandaş–avukat eşleşmesi sayısı" (mevzuata uygun modelde, dosya 11)

## 5. Birim ekonomisi
- **CAC** (müşteri edinme maliyeti) = pazarlama + satış harcaması / yeni ödeyen müşteri
- **LTV** (yaşam boyu değer) ≈ ARPU × brüt marj % / aylık churn
- **Sağlıklı:** LTV/CAC ≥ 3, CAC geri ödeme süresi ≤ 12 ay (B2C abonelikte daha kısa olmalı)
- **Yapay zeka ürünlerinde brüt marj:** Model/API maliyetini kullanıcı başı izle; ücretsiz katman kotalı olsun, önbellek ve daha küçük modellerle maliyet düşür.

## 6. Deney tasarımı

**ICE puanlama** ile fikirleri sırala: Etki (1-10) × Güven (1-10) × Kolaylık (1-10).

**Deney kartı:**
```
Hipotez:    [Değişiklik] yaparsak, [kitle] için [metrik] [%X] artar, çünkü [gerekçe].
Metrik:     Birincil + koruma metriği (ör. dönüşüm ↑ ama iade ↑ olmamalı)
Süre/örnek: En az 1-2 hafta veya istatistiksel olarak yeterli örneklem
Sonuç:      Kazandı / Kaybetti / Belirsiz → Öğrenim
```

Düşük trafikte A/B testi anlamlı sonuç vermez; büyük değişiklikleri sıralı test et (önce/sonra) ve nitel
geri bildirimle destekle.

## 7. Haftalık ritim
1. Pazartesi: Geçen haftanın metrikleri (`../sablonlar/haftalik-rapor.md`)
2. En zayıf huni aşamasını seç
3. 1-3 deney başlat
4. İçerik takvimini güncelle (kazanan formatları çoğalt)
5. Cuma: 5 müşteri konuşması/mesajı oku, öğrenimleri yaz

## 8. Kıyas değerleri (kaba, bağlama göre değişir)
- Landing page → kayıt: soğuk trafik %1-5, sıcak trafik %10-30+
- Freemium → ücretli: %2-5 (B2C), deneme → ücretli: %10-25 (kartsız deneme), %40-60 (kartlı)
- B2C abonelik aylık churn: %5-10 tipik; B2B SMB: %2-5
- Instagram etkileşim oranı (erişim bazında): %3-6 iyi; gönderme ve kaydetme oranları beğeniden daha anlamlıdır
Kıyas değerlerini hedef değil, akıl sağlığı kontrolü olarak kullan; kendi geçmişinle kıyasla.
