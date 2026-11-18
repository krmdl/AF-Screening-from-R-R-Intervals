# Dergi kartı: Biomedical Signal Processing and Control (BSPC, Elsevier)
Kaynak: https://www.sciencedirect.com/journal/biomedical-signal-processing-and-control/publish/guide-for-authors (18 Kasım 2026'da okundu; sayfa metninin son ~5,5 bin karakteri, yani kontrol listesi ve lisans bölümü, uzunluk sınırı nedeniyle okunamadı). Kılavuzda yazmayan satıra "kılavuzda yok" yazıldı.
SCImago: SJR 2025 = 1,336, Q1 (Signal Processing / Biomedical Engineering / Health Informatics).

| Satır | Kılavuzdan |
|---|---|
| Makale türü | Review (10.000 kelime); Full paper (özgün çalışma: teknik gelişme + kavramı kanıtlayan klinik/deneysel çalışma, normalde ~5.000 kelime); Short communication (~2.000 kelime, "genellikle ön nitelikte önemli gözlemler"); Technical Note (5.000 kelime, en çok 5 görsel); Perspective (davetli). |
| Uzunluk sınırı | Türe göre yukarıdaki kelime sayıları ("normally about / typically"). |
| Özet | En çok 250 kelime. Amaç, temel yöntem, ana bulgular (varsa istatistiksel anlamlılık), sonuç; tek başına anlaşılır; atıf ve yaygın olmayan kısaltma yok. |
| Anahtar kelime | 1–7, İngilizce; çok sözcüklü ("and"/"of" içeren) kelimelerden kaçının. |
| Highlights | Zorunlu: 3–5 madde, her biri en çok 85 karakter (boşluk dahil), ayrı düzenlenebilir dosya, dosya adında "highlights". |
| Graphical abstract | Teşvik ediliyor (zorunlu değil): ayrı dosya, en az 1328 piksel genişlik, 13 cm'de okunur; TIFF/EPS/PDF/MS Office. |
| Hakemlik türü | Tek yönlü anonim (single anonymized); en az iki hakem; editörler kararı verir. |
| Zorunlu beyanlar | Rekabet eden çıkarlar (deklarasyon aracı, Word dosyası yüklenir; yoksa "I have nothing to declare"); fon kaynakları (fon yoksa standart cümle); üretken yapay zekâ kullanımı (aşağıda); yazar katkısı CRediT (sorumlu yazar belirtir); araştırma verisi (aşağıda); yayın etiği ve gönderi beyanı (başka yerde yayımlanmadığı/değerlendirilmediği). Etik kurul beyanı: kılavuzda ayrı bir madde yok (Elsevier etik politikasına yönlendiriyor). |
| Veri ve kod | Seçenek C: veriyi ilgili bir veri deposuna koyun ve gönderim sırasında bağlantı verin; mümkün değilse nedenini yazın (makalede yayımlanır). Yazılım/kod ayrı atıf gerektirir (DOI tercih). |
| Kaynak biçimi | Köşeli parantezle numara, metinde geçiş sırasıyla; gönderimde herhangi bir tutarlı biçim kabul; DOI varsa yazılır; her kaynak gerçek olmalı; kabulden sonra derginin biçimi uygulanır. |
| Şekil kuralları | Her şekil ayrı dosya, metinde atıf, açıklamalı başlık (kısa başlık + açıklama); fotoğraf en az 300 dpi, çizgi çizim en az 1000 dpi; vektör için EPS/PDF; birden fazla görseli tek dosyada birleştirmeyin; renk erişilebilir olmalı. |
| LaTeX sınıfı | Kılavuzda yok. (Yalnızca: .tex dosyası kabul, çift sütun yalnız LaTeX gönderimlerde.) Elsevier'in `elsarticle` şablonu kullanılabilir ama kılavuz bunu yazmıyor: [KONTROL] |
| Yayın ücreti (APC) / erişim | Kılavuzda tutar yok. "Supports open access" yazıyor; seçenekler ayrı "open access information page"e yönlendiriliyor: [KONTROL] |
| Yapay zekâ politikası (kılavuzdan) | "Authors must declare the use of generative AI tools in the manuscript preparation process upon submission of the paper." Araçlar insan eleştirel düşüncesinin yerine geçmemeli; yalnızca insan denetimiyle kullanılabilir. Yazar doğruluktan sorumlu (kaynaklar uydurma olabilir). Araç yazar/ortak yazar olarak gösterilemez. Beyan, makalenin sonunda, kaynakçadan önceki yeni bir bölümde yer alır. Bölüm başlığı: "Declaration of generative AI and AI-assisted technologies in the manuscript preparation process". Cümle: "During the preparation of this work the author(s) used [NAME OF TOOL/SERVICE] to [REASON]. After using this tool/service, the author(s) reviewed and edited the content as needed and take(s) full responsibility for the content of the published article." Dil, yazım ve kaynak denetimi gibi temel araçlar için beyan gerekmez. Şekiller: veriden tekrarlanabilir yöntemle üretilen grafikler için yapay zekâ kullanılabilir (başlıkta ve genel beyanda belirtin); birincil gözlem/deney görüntülerini yapay zekâyla üretmek ya da değiştirmek yasak. |

## Bu sınırlar makalem için ne demek (5 madde)
1. **Tür:** Mevcut sonuçlar (tek veri kümesi, 400 kayıt, bağımsız doğrulama yok) "Full paper"ın istediği "kavramı kanıtlayan klinik/deneysel çalışma" için zayıf; bağımsız veri doğrulamasından sonra Full paper, o olmadan en fazla Short communication (~2.000 kelime, ön nitelikte gözlem).
2. **Kapsam:** Kapsam listesi "signal quality assessment, artifact detection, denoising, robustness analysis" ve ECG'yi içeriyor; ama dergi yeni yöntem ve klinik doğrulama vurguluyor. Katkımız (iki basit ölçünün karşılaştırması) yenilik düzeyinde mütevazı; dayanıklılık iddiası henüz kanıtsız.
3. **Hazırlanacaklar:** 3–5 maddelik highlights (her biri ≤ 85 karakter), ≤ 250 kelimelik özet, 1–7 anahtar kelime, CRediT katkı beyanı, rekabet eden çıkarlar ve fon beyanı.
4. **Veri/kod:** Seçenek C gereği veri deposu bağlantısı gerekli; veri PhysioNet'te açık, kod GitHub'da; kodu kalıcı kimlikli bir depoya (DOI) koymak kaynak gösterimi için uygun.
5. **Yapay zekâ:** Kullandığım araçlar için makale sonunda ayrı bölümde beyan zorunlu; metni kendi cümlelerinizle yazıp her sayıyı kendi çıktınızla doğrulamanız beklenir. Bu proje için araç adı ve kullanım amacı beyan cümlesine yazılır.
