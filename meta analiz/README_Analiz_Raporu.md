# Doruk Sağlık Grubu — Meta (Instagram/Facebook) Reklam Bütçesi Analizi

**Rapor Dönemi:** 23 Haziran 2026 – 22 Temmuz 2026 (30 günlük pencere · **26 aktif gün** veri var)
**Kaynak:** `Ads_ÖzRapor_Haz23_2026_Tem22_2026.xlsx` (762 satır günlük kampanya kaydı)
**Toplam Harcama:** **1.011.950 TL**

> Bu klasörde iki Excel var:
> - **`Doruk_Reklam_Meta_Analiz.xlsx`** — tam analiz (6 sekme): özet, kategori analizi, kampanya detayı, 60K dağıtımı, sayfa×amaç matrisi, doktor artış senaryoları.
> - **`Doruk_Butce_Kiyaslama_Raporu.xlsx`** — 2 sayfa: **"1. Özet (Pivot)"** kategori ▸ amaç açılır-kapanır pivot (soldaki −/+ ile), kolonlar **Gerçekleşen · 60K · +10K (70K) · +20K (80K)** (aylık + günlük); **"2. Kampanya Kırılımı"** kampanya seviyesine kadar kaynak tablo. Özet, kampanya kırılımından **SUMIFS ile türer**; parametreler (bütçe / Ek A / Ek B) kampanya sayfasının üstündeki sarı hücrelerdedir.
>
> Her iki dosyada da **sarı hücreler** (bütçe / ek tutarlar) değiştirilebilir; tablolar canlı formüllüdür.

---

## 1. Özet Göstergeler

| Gösterge | Değer |
|---|---|
| Toplam harcama (30 gün) | **1.011.950 TL** |
| Günlük ortalama (26 aktif gün) | **38.921 TL/gün** |
| Günlük ortalama (30 günlük pencere) | **33.732 TL/gün** |
| Toplam farklı kampanya | 58 |
| Reklam verilen sayfa sayısı | 6 (1 hastane + 1 estetik marka + 4 doktor) |

> Not: 30 günlük pencerede 4 gün (25 Haz, 7 / 12 / 19 Tem) hiç veri/harcama yok. Bu yüzden iki farklı günlük ortalama veriyoruz — "aktif gün" gerçek yayın temposunu, "30 gün" pencere ortalamasını gösterir.

---

## 2. Ana Kategori — Sayfa Tipine Göre (Hastane mi, Marka mı, Doktor mu?)

Reklamlar 3 tür sayfadan yayınlanıyor:

| Ana Kategori | Sayfa(lar) | Harcama | Pay | Günlük Ort. (30g) |
|---|---|--:|--:|--:|
| **Hastane (Kurumsal)** | Doruk Hastaneleri | **854.984 TL** | **%84,5** | 28.499 TL |
| **Estetik Marka** | Doruk Estetik & Saç Ekimi | **94.504 TL** | **%9,3** | 3.150 TL |
| **Doktor Sayfaları** | Abdullah Ertaş, Emre Çaycı, Eren Kaya, Selin Aktürk Esen | **62.462 TL** | **%6,2** | 2.082 TL |
| **TOPLAM** | | **1.011.950 TL** | **%100** | 33.732 TL |

**Tespit:** Bütçenin neredeyse tamamı (%84,5) ana kurumsal hastane sayfasından yürüyor. Doktor sayfaları ve estetik marka toplamda %15,5.

---

## 3. Kampanya Amacı — Ne İçin Harcanmış?

Her kampanyayı hedefine göre 3 ana amaca ayırdık:

| Amaç | Ne demek? | Harcama | Pay | Günlük Ort. (30g) |
|---|---|--:|--:|--:|
| **Lead Toplama (Form)** | Form doldurup hasta/başvuru kaydı toplama | **517.831 TL** | **%51,2** | 17.261 TL |
| **Instagram Öne Çıkarma** | Gönderi öne çıkarma / profil ziyareti (etkileşim + bilinirlik) | **273.557 TL** | **%27,0** | 9.119 TL |
| **Marka Bilinirliği (Erişim)** | Geniş kitleye erişim, tanınırlık | **220.562 TL** | **%21,8** | 7.352 TL |
| **TOPLAM** | | **1.011.950 TL** | **%100** | 33.732 TL |

**Tespit:** Ana amaç net biçimde **lead toplamak** (bütçenin yarısı). Geri kalan yarı, öne çıkarma (%27) ve marka bilinirliği (%22) arasında paylaşılıyor — yani "performans" ile "bilinirlik" harcaması kabaca 50/50.

---

## 4. Instagram Öne Çıkarmalar — Alt Kırılım (istediğin ayrım)

Toplam **273.557 TL** öne çıkarma harcamasının sayfa tipine göre dağılımı:

| Öne Çıkarma Grubu | Harcama | Öne çıkarma içi pay | Genel pay |
|---|--:|--:|--:|
| **Doruk Hastaneleri öne çıkarmaları** | **176.684 TL** | %64,6 | %17,5 |
| **Doktor sayfası öne çıkarmaları** | **62.462 TL** | %22,8 | %6,2 |
| **Doruk Estetik öne çıkarmaları** | **34.411 TL** | %12,6 | %3,4 |

**Doktor öne çıkarmaları — doktor bazında:**

| Doktor | Harcama |
|---|--:|
| Op.Dr. Abdullah Ertaş | 19.973 TL |
| Op. Dr. Emre Çaycı | 18.781 TL |
| Op.Dr. Eren Kaya | 13.393 TL |
| Doç.Dr. Selin Aktürk Esen | 10.314 TL |

> Not: Doktor sayfalarındaki tüm harcama %100 "Instagram öne çıkarma" niteliğinde — doktor sayfalarında lead/erişim kampanyası yok, sadece gönderi öne çıkarma yapılmış.

---

## 5. Lead Toplama — Konu Bazında Alt Kırılım

517.831 TL lead bütçesi hangi hizmetlere gitmiş:

| Lead Alt Kategorisi | Harcama | Lead içi pay |
|---|--:|--:|
| **Kadın Doğum / Gebe / FTR** | 271.314 TL | %52,4 |
| **Estetik / Plastik Cerrahi / Saç Ekimi** (ABO/CBO kampanyaları) | 153.934 TL | %29,7 |
| **İK / İş Başvurusu** (hemşire, uzman hekim) | 48.191 TL | %9,3 |
| **Check-up / Sağlık Taraması** | 44.391 TL | %8,6 |

**Tespit:** Lead bütçesinin yarısı gebe/doğum hattına, üçte biri estetik-plastik cerrahiye gidiyor. İlginç bir kalem: bütçenin ~%4,8'i (48 bin TL) hasta değil, **personel (İK) başvurusu** toplamak için harcanmış.

---

## 6. Marka Bilinirliği (Erişim) — Alt Kırılım

| Bilinirlik Kampanyası | Harcama |
|---|--:|
| Doktor - Bilinirlik (Nilüfer + Yıldırım) | 150.909 TL |
| Kurumsal (ÖSS-TSS marka bilinirliği) | 46.163 TL |
| Gebe-Doğum Bilinirlik | 23.490 TL |

---

## 7. Günlük 60.000 TL Senaryosu — Aynı Oranlarla Dağıtım

Geçmiş 30 günün harcama oranları **birebir korunarak**, günlük **60.000 TL** bütçenin nasıl dağıtılacağı aşağıdadır. (Aylık = günlük × 30)

### 7A. Ana Kategoriye Göre

| Ana Kategori | Pay | Günlük (TL) | Aylık (TL) |
|---|--:|--:|--:|
| Hastane (Kurumsal) | %84,5 | **50.716 TL** | 1.521.480 TL |
| Estetik Marka | %9,3 | **5.605 TL** | 168.150 TL |
| Doktor Sayfaları | %6,2 | **3.704 TL** | 111.120 TL |
| **TOPLAM** | %100 | **60.000 TL** | 1.800.000 TL |

### 7B. Kampanya Amacına Göre

| Amaç | Pay | Günlük (TL) | Aylık (TL) |
|---|--:|--:|--:|
| Lead Toplama (Form) | %51,2 | **30.708 TL** | 921.240 TL |
| Instagram Öne Çıkarma | %27,0 | **16.222 TL** | 486.660 TL |
| Marka Bilinirliği (Erişim) | %21,8 | **13.080 TL** | 392.400 TL |
| **TOPLAM** | %100 | **60.000 TL** | 1.800.000 TL |

### 7C. Detaylı Alt Kategorilere Göre (Tam Kırılım)

| Alt Kategori | Pay | Günlük (TL) | Aylık (TL) |
|---|--:|--:|--:|
| Lead - Kadın Doğum / Gebe / FTR | %26,8 | 16.087 TL | 482.610 TL |
| Lead - Estetik / Plastik / Saç | %15,2 | 9.128 TL | 273.840 TL |
| Lead - Check-up / Tarama | %4,4 | 2.632 TL | 78.960 TL |
| Lead - İK / İş Başvurusu | %4,8 | 2.857 TL | 85.710 TL |
| Öne Çıkarma - Doruk Hastaneleri | %17,5 | 10.476 TL | 314.280 TL |
| Öne Çıkarma - Doktor | %6,2 | 3.704 TL | 111.120 TL |
| Öne Çıkarma - Doruk Estetik | %3,4 | 2.040 TL | 61.200 TL |
| Bilinirlik - Doktor Tanıtım | %14,9 | 8.947 TL | 268.410 TL |
| Bilinirlik - Kurumsal (ÖSS-TSS) | %4,6 | 2.737 TL | 82.110 TL |
| Bilinirlik - Gebe / Doğum | %2,3 | 1.393 TL | 41.790 TL |
| **TOPLAM** | %100 | **60.000 TL** | 1.800.000 TL |

> **Önemli:** Günlük 60.000 TL, mevcut günlük ortalamanın (≈33.700–38.900 TL) yaklaşık **1,55–1,78 katı**. Yani oranları koruyarak her kalemi kabaca %55–78 büyütmüş oluyorsunuz. Excel'deki sarı hücreyi değiştirerek 60.000 dışında herhangi bir bütçeyi de anında hesaplatabilirsiniz.

---

## 8. Sayfa Kategorisi × Amaç Matrisi (istediğin çapraz tablo)

Her sayfa kategorisinin altında amaçlar, tutar + oran ve günlük 60.000 TL karşılığı. **Genel %** = toplam bütçedeki pay, **Sayfa-İçi %** = o sayfanın kendi içindeki dağılım.

| Sayfa Kategorisi | Amaç | Harcama (30g) | Genel % | Sayfa-İçi % | Günlük (60K) |
|---|---|--:|--:|--:|--:|
| **Hastane (Kurumsal)** | Lead Toplama (Form) | 457.738 TL | %45,2 | %53,5 | 27.140 TL |
| | Instagram Öne Çıkarma | 176.684 TL | %17,5 | %20,7 | 10.476 TL |
| | Marka Bilinirliği (Erişim) | 220.562 TL | %21,8 | %25,8 | 13.080 TL |
| | **Hastane ALT TOPLAM** | **854.984 TL** | **%84,5** | %100 | **50.693 TL** |
| **Estetik Marka** | Lead Toplama (Form) | 60.093 TL | %5,9 | %63,6 | 3.563 TL |
| | Instagram Öne Çıkarma | 34.411 TL | %3,4 | %36,4 | 2.040 TL |
| | **Estetik ALT TOPLAM** | **94.504 TL** | **%9,3** | %100 | **5.604 TL** |
| **Doktor Sayfaları** | Instagram Öne Çıkarma | 62.462 TL | %6,2 | %100 | 3.704 TL |
| | **Doktor ALT TOPLAM** | **62.462 TL** | **%6,2** | %100 | **3.704 TL** |
| | **GENEL TOPLAM** | **1.011.950 TL** | **%100** | | **60.000 TL** |

**Tespit:** Estetik marka ve doktor sayfalarında hiç "Marka Bilinirliği (Erişim)" kampanyası yok. Doktor sayfaları %100 öne çıkarma. Hastane sayfası içinde ise dağılım: yarısı lead (%53,5), dörtte biri bilinirlik (%25,8), beşte biri öne çıkarma (%20,7).

> Excel'de bu tablo **"5. Sayfa x Amaç Matrisi"** sekmesinde canlı formüllüdür; oradaki sarı bütçe hücresini değiştirerek günlük/aylık karşılıkları anında güncelleyebilirsin.

---

## 9. Günlük 60.000 TL — 3 Doktor Artış Senaryosu

**Varsayım (senin belirttiğin gibi):** Ödeme durunca/başlayınca her kalem oranlı hareket eder; bu yüzden baz 60K dağılımı geçmiş oranlarla kurulur. **Ek bütçe yalnızca doktor sayfalarına, üstüne eklenir**; Hastane ve Estetik kalemleri üç senaryoda da **sabit** kalır.

- **Senaryo 1 — Baz 60K:** 60.000 TL geçmiş oranlarla dağıtılır (doktor payı ≈ %6,2).
- **Senaryo 2 — Doktora +10K:** Baz dağılım + doktora ek 10.000 TL → günlük toplam **70.000 TL**.
- **Senaryo 3 — Doktora +20K:** Baz dağılım + doktora ek 20.000 TL → günlük toplam **80.000 TL**.

### Günlük Dağılım (TL/gün)

| Sayfa Kategorisi | Senaryo 1 (Baz 60K) | Senaryo 2 (+10K) | Senaryo 3 (+20K) |
|---|--:|--:|--:|
| Hastane (Kurumsal) | 50.693 | 50.693 | 50.693 |
| Estetik Marka | 5.604 | 5.604 | 5.604 |
| **Doktor Sayfaları** | **3.704** | **13.704** | **23.704** |
| **GÜNLÜK TOPLAM** | **60.000** | **70.000** | **80.000** |
| → Doktor payı (% toplam) | %6,2 | %19,6 | %29,6 |

### Aylık Dağılım (TL/ay = günlük × 30)

| Sayfa Kategorisi | Senaryo 1 | Senaryo 2 | Senaryo 3 |
|---|--:|--:|--:|
| Hastane (Kurumsal) | 1.520.790 | 1.520.790 | 1.520.790 |
| Estetik Marka | 168.120 | 168.120 | 168.120 |
| **Doktor Sayfaları** | **111.120** | **411.120** | **711.120** |
| **AYLIK TOPLAM** | **1.800.000** | **2.100.000** | **2.400.000** |

### Doktor Bazında Günlük (ek, geçmiş paya göre 4 doktora bölünür)

| Doktor | Doktor-içi pay | Senaryo 1 | Senaryo 2 | Senaryo 3 |
|---|--:|--:|--:|--:|
| Op.Dr. Abdullah Ertaş | %32,0 | 1.184 | 4.382 | 7.580 |
| Op. Dr. Emre Çaycı | %30,1 | 1.114 | 4.120 | 7.127 |
| Op.Dr. Eren Kaya | %21,4 | 794 | 2.938 | 5.083 |
| Doç.Dr. Selin Aktürk Esen | %16,5 | 612 | 2.263 | 3.914 |
| **DOKTOR TOPLAM** | %100 | **3.704** | **13.704** | **23.704** |

**Tespit:** Doktor sayfalarına 60K içindeki payı (%6,2) korunarak değil de sabit ek yaparak yaklaşırsak, doktorların toplam bütçedeki ağırlığı Senaryo 2'de ~%20'ye, Senaryo 3'te ~%30'a çıkıyor — hastane/estetik harcamasını hiç azaltmadan. Excel'deki **"6. Doktor Artış Senaryoları"** sekmesinde ek tutarları (10K/20K) sarı hücrelerden değiştirebilirsin.

---

## 10. Kategori Sözlüğü (Metodoloji)

Sınıflandırma kampanya adı + sayfa adı + sonuç türü üzerinden yapıldı:

- **Ana Kategori (sayfa tipi):** Sayfa adına göre → Hastane / Estetik Marka / Doktor.
- **Kampanya Amacı:**
  - Adı "Instagram gönderisi" / "Gönderi" ile başlayan → **Instagram Öne Çıkarma**
  - Adında "bilinirlik" / "ÖSS-TSS" geçen → **Marka Bilinirliği (Erişim)**
  - Diğer tüm form/lead/başvuru/checkup/ABO/CBO/FTR kampanyaları → **Lead Toplama (Form)**
- **Alt kategoriler:** Lead içinde konu (gebe-doğum, estetik/plastik, check-up, İK); öne çıkarma içinde sayfa grubu (hastane/doktor/estetik); bilinirlik içinde tema.

Tüm ham veri ve kategori etiketleri Excel'deki **"Ham Veri (Kategorili)"** sekmesinde satır satır bulunabilir; oradan filtreleyerek her rakamı doğrulayabilirsiniz.
