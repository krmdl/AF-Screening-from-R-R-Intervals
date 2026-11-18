# İddia tablosu (Hafta 1 taslağı)

**Katkı cümlesi (geçici):** On the same 400 PhysioNet/CinC 2017 records and with the same R-peak detector and threshold rule (threshold chosen on development records only), a median-based R–R irregularity measure (MDR) reached a higher AF F1 than the standard-deviation-based CV (0.826 vs 0.747 on 200 test records), mainly through higher specificity; whether MDR is more robust to R-peak errors is not yet shown.

| # | İddia | Kanıt | Şekil / tablo | Durum |
|---|---|---|---|---|
| 1 | MDR, geliştirmede seçilen eşikle test kümesinde CV'den yüksek AF F1 verir (0,826 ve 0,747). | README ana tablo, notebook hücre 1; test 100 AF + 100 normal, TP/FN/FP/TN verildi. | Şekil 1 (`fig1_scores.png`), Tablo 1 | Kanıtlı. Fark 0,079, bootstrap GA ve McNemar p = 0,0002 yerel çalıştırmadan: [KONTROL] Colab'da son hücre çalıştırılacak. |
| 2 | Fark, eşiğin hangi yarıda seçildiğine bağlı değil (rol değişimi: CV 0,752; MDR 0,833; fark 0,081). | `analiz\rol\RAPOR.md` ve `cikti.txt` (depoda yok). | Tablo 2 | Yerel kanıt var, depoya betik konmalı: [KONTROL] |
| 3 | Üstünlük tek bir ayrıma bağlı değil: 200 rastgele 100+100 ayrımda MDR'nin test F1'i 200/200 yüksek, ortalama fark 0,073. | `analiz\istatistik\RAPOR.md` (depoda yok). | Tablo 3 | Yerel kanıt var, depoya betik konmalı: [KONTROL] |
| 4 | Üstünlüğün kaynağı özgüllük (0,34 → 0,72); duyarlılık düşer (0,99 → 0,90). CV'nin 66 yanlış pozitifinden 43'ü MDR'de doğru. | Karışıklık matrisi; `analiz\hata\RAPOR.md`. | Şekil 4 (örnek kayıtlar: A00222, A00223, A00303) | Kanıtlı (hata analizi yerel): [KONTROL] |
| — | **Ertelenen / yazılmayacak:** "MDR R tepesi hatalarına daha dayanıklıdır." | Gürültü katmanında fark artmadı (temiz 0,093; orta 0,103; gürültülü 0,041); benzetimde CV'nin çöküşü büyük ölçüde donmuş eşikten. | Şekil 2–3 (benzetim) | **Kanıtsız**: 3. haftanın deney planına (bağımsız veri, gerçek hata) ya da silinecek. |

Yazmayın: "novel", "robust", "diagnoses". Yazın: "screening", "research-oriented".
Sınırlılık: kişi kimliği yok, tek veri kümesi (400 kayıt), test dengeli (100/100).
