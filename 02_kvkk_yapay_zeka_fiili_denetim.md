# 🇹🇷 Geleceği Beklemeyin: KVKK Zaten Yapay Zekânızı Denetliyor

**TL;DR:** Türkiye'nin çerçeve yapay zeka kanunu (2/2234) komisyonda beklerken, startup'ların yapay zeka ürünlerini fiilen denetleyen aktif bir otorite halihazırda var: **Kişisel Verileri K[...]

## ⚖️ Startup'lar İçin 3 Kritik Yasal Cephe

### 1. Otomatik Kararlar (Algoritmik Sonuçlara İtiraz)
KVKK Madde 11, kişinin verilerinin *münhasıran otomatik sistemlerle* analiz edilip aleyhine bir sonuç çıkması halinde itiraz hakkı tanır. GDPR'dan farklı olarak genel bir yasak değil, it[...]

* **Risk Altındaki Ürünler:** CV eleme ve aday sıralama (HR-Tech), kredi ve fraud skorlama (Fintech), dinamik fiyatlama, içerik moderasyonu ve otomatik hesap askıya alma motorları.
* **Geliştirici & Ürün Ekibi İçin Çözüm:**
    * Aleyhe otomatik sonuçlar için mutlaka bir **"İnsan İncelemesi" (Human-in-the-loop)** mekanizması (Fallback) kurun.
    * Aydınlatma metninizde "otomatik analiz" yapıldığını açıkça belirtin.
    * *"Model öyle karar verdi (Blackbox)"* savunması geçersizdir; sonucun nasıl üretildiğini (en azından sistem düzeyinde / Explainable AI) açıklayabilecek bir altyapı tasarlayın.

### 2. Biyometrik Doğrulama (Yüz ve Ses Tanıma)
Kurulun mesai takibinde biyometrik veriye ilişkin 2026/921 sayılı ilke kararı, biyometri alanında Türkiye'deki standartları belirler.

* **Temel Kural:** Biyometrik veri özel nitelikli kişisel veridir. Açık rıza tek başına orantısız bir sistemi kurtarmaz.
* **Gereklilik Testi:** Daha az müdahaleci bir alternatif (PIN, şifre, kart vb.) varken biyometrik yol (örneğin yol haritanızdaki "Yüzünüzle doğrulayın" özelliği) **gereklilik testini [...]

### 3. Eğitim Verisi (Data Scraping) ve YZ Üretimi İçerik
LLM ve GenAI modelleriniz eğitim verisiyle çalışır ve bu veri kişileri içeriyorsa tüm temel KVKK ilkeleri (hukuki sebep, amaçla sınırlılık, veri minimizasyonu, saklama süreleri) devr[...]

* Türk kullanıcı verisini *hukuki bir sebep olmadan* eğitmek (scraping) geleceğin değil, **bugünün sorunudur.**
* **Çıktı (Output) Riski:** Kasım 2025 tarihli TCK tasarısı, yapay zeka üretimi sentetik içeriklere (deepfake vb.) yönelik ciddi yaptırımlar öngörmektedir. (Bkz: AI Watermarking)

---

> 💡 **Uyarı:** Bir startup'ın yapay zeka ürünü geliştirirken atması gereken ilk adım "Sınıflandırma Memosu" (yasaklı, yüksek riskli, şeffaflık, asgari risk) hazırlamaktır.
> 
> *Daha detaylı hukuki analiz ve Vircon Legal Yapay Zeka Uyum Merkezi içgörüleri için orijinal metin: [KVKK Zaten Yapay Zekânızı Denetliyor - Vircon Legal](https://virconlegal.com/tr/kvkk-[...]


erdem mümtaz hacıpaşaoğlu tarafından yazılmıştır
