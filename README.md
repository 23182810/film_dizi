# 🎬 Kişiselleştirilmiş Dizi ve Film Öneri Sistemi

**Ders:** BLM0324 - Yazılım Mühendisliği  
**Dönem:** Bahar 2025  
**Takım Numarası:** 5  

## 📌 Proje Amacı

Günümüzde dijital içerik platformlarında binlerce film ve diziye erişmek mümkün. Ancak kullanıcıların ilgi alanlarına uygun içerikleri keşfetmesi zaman alabilir ve çoğu zaman tatmin edici önerilere ulaşmak zor olabilir.  
Bu projede, kullanıcıların izleme alışkanlıklarını analiz ederek **kişiselleştirilmiş öneriler sunan yapay zeka destekli bir web platformu** geliştirilmiştir.

Platform, kullanıcıların daha önce izledikleri yapımlar, beğenileri, yorumları ve tercih ettikleri türleri temel alarak önerilerde bulunur. Bu sayede her kullanıcıya özel, dinamik ve güncel bir izleme deneyimi sunulur.

---

## 🎯 Proje Hedefleri

- 🎯 Kullanıcılara en uygun içerikleri sunarak izleme deneyimini kişiselleştirmek  
- 🔍 İçerik arama ve keşfetme sürecini kolaylaştırmak ve hızlandırmak  
- 🧠 Yapay zeka temelli filtreleme algoritmaları ile öneri doğruluğunu artırmak  
- 💬 Kullanıcı etkileşimini teşvik ederek sosyal bir içerik topluluğu oluşturmak  
- 🌐 Güncel verilerle çalışan esnek ve genişletilebilir bir öneri sistemi tasarlamak  

---

## 👥 Takım Üyeleri ve Görev Dağılımı

| İsim               | Görevler                                                                 |
|--------------------|--------------------------------------------------------------------------|
| **Huri Nisa İnsan** | İletişim sorumlusu, Fikir geliştirme, Tasarım süreci                    |
| **Ceyda Gülen**     | Kullanıcı arayüzü geliştirme, Sayfa yönlendirmeleri                     |
| **Sude Naz Doğdu**  | Giriş/Favori/Puanlama işlevleri                                         |
| **Özge Keskin**     | Mock verilerle test, Sunucu kurulumu (Express.js)                       |
| **Erva Aygüneş**    | Veritabanı bağlantısı, Backend entegrasyonu, Kullanıcı arayüzü geliştirme |
| **Zeynep Erarslan** | Kullanıcı arayüzü geliştirme, Backend entegrasyonu, API bağlantıları     |

---

## 🛠️ Kullanılan Teknolojiler

- **Frontend:** React.js  
- **Backend:** Node.js & Express.js  
- **Veritabanı:** MySQL  
- **Yapay Zeka:** İçerik bazlı filtreleme + İşbirlikçi filtreleme  
- **Veri Kaynakları:** TMDb API, IMDb API, OMDb API  
- **Araçlar:** Git, GitHub, Canva, Excel, VSCode  

---

## 🔍 Öne Çıkan Özellikler

- 🔎 Gerçek zamanlı arama ve otomatik tamamlama  
- 📋 Kişiselleştirilmiş öneri listeleri  
- 🧠 Yapay zeka destekli gelişmiş öneri motoru  
- 💬 Yorum yapma ve favorilere ekleme sistemi  
- 🗂️ Kullanıcı profili ve izleme geçmişi analizi  
- 📈 Dinamik olarak güncellenen içerik önerileri  

---

## 📎 Proje Belgeleri

- 📄 `proje_detayı.pdf` – Proje kapsamı ve işleyişi  
- 📘 `katalog.pdf` – Ürün tanıtım kataloğu  
- 📚 `kullanımkılavuzu.pdf` – Uygulama kullanım rehberi  
- 🧾 `hikayekartlari.pdf` – Kullanım senaryoları ve kullanıcı hikayeleri  
- 📑 `gereksinim_dokumani.pdf` – Fonksiyonel ve fonksiyonel olmayan gereksinimler  

---

## 🧩 Sistem Mimarisi

1. **Kayıt ve Giriş:** Kullanıcılar sistemde profil oluşturur.  
2. **Veri Toplama:** Beğenilen türler, geçmiş, puanlamalar ve yorumlar toplanır.  
3. **Analiz:** Yapay zeka algoritmaları ile kullanıcı alışkanlıkları analiz edilir.  
4. **Öneri Üretimi:** İçerik bazlı + işbirlikçi filtreleme + hibrit model  
5. **Etkileşim:** Kullanıcılar önerileri favorilere alabilir, puanlayabilir, yorum yapabilir.  
6. **Geri Bildirim:** Sistem kullanıcı davranışlarıyla kendini geliştirir.  

---

## 📥 Kurulum Adımları

### Backend Kurulumu

```bash
cd backend
npm install
npm start

