# 💧 Sentetik İçerik ve AI Watermarking (Yapay Zeka Filigranı) Yükümlülükleri

**TL;DR:** Ürettiğiniz metin, görsel, ses veya video makine yapımıysa (GenAI), bunun bir yapay zeka tarafından üretildiğinin makine tarafından okunabilir bir "filigran" (watermark) ile işaretlenmesi zorunlu hale geliyor. 

## 🇪🇺 EU AI Act Madde 50: Şeffaflık Zorunluluğu

Eğer sisteminiz yapay zeka ile görsel, ses veya video üretiyorsa/manipüle ediyorsa (Deepfake), Avrupa pazarında aşağıdaki kurallara uymak zorundasınız (Zorunluluk Başlangıcı: 2 Ağustos 2026):

1. **Görünür İfşa:** İçeriğin yapay zeka tarafından üretildiği veya manipüle edildiği son kullanıcıya açıkça bildirilmelidir.
2. **Makine Okunabilir Filigran:** Sadece metinle "AI tarafından üretildi" yazmak yetmez. EXIF verisine, C2PA standartlarına veya kriptografik yöntemlere dayanan teknik bir işaretleme mimarisi (watermarking) ürününüze entegre edilmelidir.
3. **İstisnalar:** Kolluk kuvvetlerinin kullanımı veya ifade özgürlüğü (sanat/parodi) kapsamındaki bazı spesifik alanlar hariç tutulmuştur ancak ticari ürünlerin tamamı kapsama girer.

## 🇹🇷 Türkiye'deki Paralel Gelişmeler

Avrupa'daki bu tüzüğün yanı sıra, Türkiye'de de sentetik içeriğin cezai boyutunu düzenleyen yasa tasarıları gündemdedir. 
* Özellikle bir kimsenin ses veya görüntüsünü rızası dışında manipüle eden (Deepfake) araçların sağlayıcıları, "çıktıyı işaretlemedikleri" takdirde ağır müteselsil sorumluluklarla karşılaşabilirler.
* **Geliştirici Tavsiyesi:** İçerik üretici (GenAI) bir SaaS yapıyorsanız, filigranlama altyapısını bir "gelecek vizyonu" değil, "lansman ön koşulu" (MVP Requirement) olarak ürün yol haritanıza (roadmap) ekleyin.

---
*💡 Deepfake regülasyonları ve teknik şeffaflık zorunlulukları hakkında detaylı okuma için: [Vircon Legal Sözlük - AI Watermarking](https://virconlegal.com)*
