# 🤖 Yapay Zeka Ajanları (Agentic AI) Otonom İşlem Yaparsa Kim Sorumlu?

**TL;DR:** Klasik LLM'ler (ChatGPT vb.) metin üretir; Yapay Zeka Ajanları (Agentic AI) ise sizin adınıza işlem yapar (API çağırır, uçak bileti alır, sözleşme onaylar). Ajanların bu otonomisi, hukuktaki "içerik riskini" doğrudan **"eylem ve tazminat riskine"** dönüştürür.

## ⚖️ Geliştiriciler İçin Hukuki Basınç Noktaları

### 1. Borçlar Hukuku ve "Ajanın Temsil Yetkisi"
Sizin kodladığınız bir yapay zeka ajanı, müşterinizin adına yanlış bir sipariş verir veya limitleri aşarsa, ortaya çıkan zararı kim karşılayacak? 
* **Hukuki Durum:** Birçok hukuk sisteminde "kodun yaptığı işlem", o kodu canlıya alan şirketin veya kullanıcının iradesi sayılır.
* **Sözleşmesel Çözüm (ToS):** B2B veya B2C Kullanım Şartları (Terms of Service) metinlerinizde ajanın "yetki sınırları", "harcama tavanları" ve "yanlış API çağrılarından doğacak sorumluluk retleri" açıkça kodlanmalıdır.

### 2. "Human-in-the-Loop" (İnsan Onayı) Mimarisi
Ajanların kritik işlemlerde (örn: para transferi, kalıcı veri silme) tek başına karar vermesi hukuken savunulması en zor mimaridir.
* **Tasarım Önerisi:** Ajan her şeyi planlayabilir ancak nihai `Execute` (Çalıştır) emri için sistemin kullanıcıdan bir onay (Prompt/Click) istemesi, sorumluluğu yazılımdan kullanıcıya aktarır.

### 3. Loglama ve Denetim İzleri (Audit Trails)
Bir uyuşmazlık çıktığında mahkemeye veya KVKK Kuruluna sunabileceğiniz tek şey log kayıtlarınızdır.
* Ajanın hangi prompt ile tetiklendiği, hangi araçları (tools/API) kullandığı ve hangi kararı neden aldığı kriptografik ve değiştirilemez bir log altyapısıyla saklanmalıdır.

---
*💡 Otonom sistemlerin sözleşme hukuku ve EU AI Act kapsamındaki analizi için: [Vircon Legal Sözlük - Agentic AI](https://virconlegal.com)*
