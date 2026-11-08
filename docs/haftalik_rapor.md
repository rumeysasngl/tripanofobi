# Araştırma Yöntem ve Teknikleri - 6. Hafta Çalışma Raporu

**Proje Adı:** Tripanofobi (İğne Korkusu) İkincil Veri Analiz ve Simülasyon Aracı
**Geliştirici / Görev Sahibi:** Rumeysa Şengül (Tüm süreçlerin planlanması, kodlanması ve sürüm takibi bireysel olarak yürütülmektedir)
**GitHub Pano ve Repo Bağlantısı:** https://github.com

---

### 📊 Bilimsel Değerlendirme ve Bulgular (Hoca Kriterlerine Göre)
1. **Veri Kaynağı:** Bu çalışmada ders yönergelerine tam uyumlu olarak doğrudan katılımcılardan (Google Forms, anket veya görüşme yoluyla) veri toplanmamış; PubMed tabanlı literatür taraması sonucu elde edilen ve iğne korkusunu ölçen 5 adet bağımsız, hakemli bilimsel yayının ikincil verileri referans alınmıştır.
2. **Ölçüm Birimi:** Analiz edilen bağımsız ve bağımlı değişkenler (kadın fobi oranı, çocukluk travma etkisi, genel prevalans) hakemli makalelerin bulgularındaki yüzde (%) ve frekans dağılım birimleri cinsinden sisteme entegre edilmiştir.
3. **Temel Bulgu:** Yapılan betimsel analiz ve kütüphane çıktısı (Matplotlib grafik modellemesi) sonucunda, incelenen tüm yayınlarda tripanofobinin başlangıç noktasının %80'in üzerinde çocukluk dönemi öğrenilmiş travmatik deneyimlere dayandığı ve kadın cinsiyetinde etki düzeyinin erkeklere oranla istatistiksel olarak daha yüksek seyretmektedir.
4. **Sınırlılık:** Elde edilen sonuçlar ve üretilen sentetik veri matrisi, tamamen seçilen 5 makalenin bölgesel örneklem sınırları (Mısır, Suudi Arabistan, Ürdün vb.) ve ikincil veri kısıtları ile sınırlıdır; küresel genel popülasyonu mutlak düzeyde temsil etmez.

---

### 📜 Veri Lisansı, Güvenlik ve Kaynak Bildirimi (Veri Sözlüğü)

Bu projede kullanılan tüm sayısal parametreler, aşağıda listelenen açık erişimli (Open Access) ve telif hakkı adil kullanım (Fair Use / CC-BY) ilkelerine sahip hakemli bilimsel yayınlardan derlenmiştir. Çalışmada hiçbir canlı katılımcıya ait kişisel veri (KVKK kapsamında ad, soyad, e-posta vb.) veya sisteme ait gizli API/Token anahtarı yer almamaktadır.

| Veri Seti / Yayın Adı | Kaynağı ve Bağlantısı | Uygulanan Lisans Türü | Analiz Edilen Ölçü Birimi |
| :--- | :--- | :--- | :--- |
| **Needle phobia among adult Jordanians...** (Almahayni et al., 2023) | [PubMed - 37729191](https://nih.gov) | CC BY 4.0 (Açık Erişim) | Cinsiyet Dağılımı (%) / Korku Skorları |
| **Prevalence, factors associated and management...** (Al-Raddadi et al., 2024) | [PubMed - 38745314](https://nih.gov) | CC BY-NC (Akademik Kullanım) | Çocukluk Dönemi Başlangıç Oranı (%) |
| **The fear of needles: A systematic review...** (McLenon & Rogers, 2019) | [PubMed - 30109720](https://nih.gov) | Wiley Open Access (Atıf İzinli) | Yaş ve Prevalans Korelasyon Oranları |
| **Managing needle-fear and pain...** (McMurtry, 2022) | [PMC - PMC9678288](https://nih.gov) | Oxford Academic (Eğitim İzinli) | Çocukluk Çağı Travma Faktörleri (%) |
| **Development and validation of the MFIS...** (Son et al., 2022) | [PubMed - 36051458](https://nih.gov) | JAN Open (Akademik Geçerlilik) | Çok Boyutlu Ölçek Katsayıları |


### ⚙️ Çalışma Zamanı ve Altyapı Notları
Analizler Google Colab sanal çalışma zamanı (CPU) üzerinde Pandas ve Matplotlib kütüphaneleri kullanılarak yürütülmüştür. Kod hücreleri ve Markdown açıklamaları yeniden üretilebilirlik ilkesine uygun olarak yapılandırılmış, elde edilen `tripanofobi_ozet.csv` tablosu ile `tripanofobi_grafik.png` veri görselleri kalıcı olarak sürüm kontrol sistemine (GitHub) commit edilmiştir.
