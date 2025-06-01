# film_dizi
🎬 Kişiselleştirilmiş Dizi ve Film Öneri Sistemi
BLM0324 - Yazılım Mühendisliği Dönem Projesi
Takım Numarası: 5
Dönem: Bahar 2025

📌 Proje Amacı
Günümüzde dijital içerik platformlarında binlerce film ve diziye erişmek mümkün. Ancak kullanıcıların ilgi alanlarına uygun içerikleri keşfetmesi zaman alabilir ve çoğu zaman tatmin edici önerilere ulaşmak zor olabilir. Bu sorunu çözmek adına geliştirdiğimiz bu proje, kullanıcıların içerik izleme alışkanlıklarını analiz ederek kişiselleştirilmiş dizi ve film önerileri sunan, yapay zeka destekli bir web platformudur.

Platform, kullanıcıların daha önce izledikleri yapımlar, beğenileri, yorumları ve tercih ettikleri türleri temel alarak önerilerde bulunur. Bu sayede her kullanıcıya özel, dinamik ve güncel bir izleme deneyimi sunulmuş olur.

🎯 Proje Hedefleri
🎯 Kullanıcılara en uygun içerikleri sunarak izleme deneyimini kişiselleştirmek
🔍 İçerik arama ve keşfetme sürecini kolaylaştırmak ve hızlandırmak
🧠 Yapay zeka temelli filtreleme algoritmaları ile öneri doğruluğunu artırmak
💬 Kullanıcı etkileşimini teşvik ederek sosyal bir içerik topluluğu oluşturmak
🌐 Güncel verilerle çalışan esnek ve genişletilebilir bir öneri sistemi tasarlamak
👥 Takım Üyeleri ve Görevleri
İsim	Görevler
Huri Nisa İnsan	İletişim sorumlusu, Fikir geliştirme, Tasarım süreci
Ceyda Gülen	Kullanıcı arayüzü geliştirme, Sayfa yönlendirmeleri
Sude Naz Doğdu	Giriş/favori/puanlama işlevleri
Özge Keskin	Mock verilerle test, Sunucu kurulumu (Express.js)
Erva Aygüneş	Veritabanı bağlantısı, Backend entegrasyon, Kullanıcı arayüzü geliştirme
Zeynep Erarslan	Kullanıcı arayüzü geliştirme, Backend entegrasyon, API bağlantıları
🛠️ Kullanılan Yazılım ve Donanım Teknolojileri
Bu proje, modern web teknolojileri ve güçlü açık kaynak araçları kullanılarak geliştirilmiştir:

Frontend: React.js, responsive ve kullanıcı dostu arayüz tasarımı
Backend: Node.js & Express.js ile RESTful API mimarisi
Veritabanı: MySQL (kullanıcı, içerik, yorum ve favori takibi için)
Yapay Zeka: İçerik bazlı filtreleme + işbirlikçi filtreleme algoritmaları
Veri Kaynakları: TMDb API, IMDb API, OMDb API ile içerik verileri
Araçlar: Git, GitHub, Canva (tasarım), Excel (iş planı), VSCode
🔍 Öne Çıkan Özellikler
🔎 Gerçek zamanlı arama ve otomatik tamamlama özelliği
📋 Kişiselleştirilmiş öneri listeleri
🧠 Gelişmiş yapay zeka destekli öneri motoru
💬 Yorum yapma ve favorilere ekleme sistemi
🗂️ Kullanıcı profili ve izleme geçmişi analizi
📈 Dinamik olarak güncellenen içerik önerileri
📎 Proje Belgeleri
Projenin gelişim sürecini ve detaylarını içeren tüm belgeler aşağıda sunulmuştur:

📄 proje_detayı.pdf – Proje kapsamı ve işleyişi
📘 katalog.pdf – Ürün tanıtım kataloğu
📚 kullanımkılavuzu.pdf – Uygulama kullanım rehberi
🧾 hikayekartlari.pdf – Kullanım senaryoları ve kullanıcı hikayeleri
📑 gereksinim_dokumani.pdf – Fonksiyonel ve fonksiyonel olmayan gereksinimleri içeren teknik doküman
🧩 Sistem Mimarisi
Kayıt ve Giriş: Kullanıcılar sistemde profil oluşturur ve oturum açar.
Veri Toplama: Beğenilen türler, izleme geçmişi, puanlamalar ve yorumlar toplanır.
Analiz ve Öğrenme: Yapay zeka algoritmaları ile kullanıcı tercihi analiz edilir.
Öneri Üretimi: İçerik bazlı, işbirlikçi ve hibrit filtreleme modelleri ile öneriler sunulur.
Etileşim: Kullanıcılar önerileri favoriye alabilir, puanlayabilir, yorum yazabilir.
Geri Bildirim: Sistem, kullanıcının aksiyonlarını izleyerek öneri motorunu geliştirir.
📥 Kurulum Adımları
# Backend kurulumu
cd backend
npm install
npm start

# Frontend kurulumu
cd frontend
npm install
npm start
.env dosyasına TMDb API anahtarı ve veritabanı bilgilerini eklemeyi unutmayın.

💡 Kullanım Senaryosu
🎞 Ali, film ve dizi izlemeyi seven bir kullanıcıdır. Sisteme giriş yaptıktan sonra:

Beğendiği türleri (bilim kurgu, aksiyon) seçer.
Daha önce izlediği yapımları puanlar.
Sistem ona özel içerik önerileri sunar.
Aradığı yapımları hızlıca bulur.
İzlediği içeriklere yorum yapar, favorilere ekler.
Bu deneyim, diğer kullanıcılar için de benzer şekilde işlemekte olup sistem her kullanıcı için farklı sonuçlar üretmektedir.

🌐 LinkedIn Paylaşımı
Tüm takım üyeleri ve danışman valuntas@gmail.com LinkedIn paylaşımında etiketlenecektir.
Proje broşürü ve GitHub linki paylaşımda yer alacaktır.
Takım üyeleri kendi kişisel profillerinde de projeyi paylaşacaktır.
📧 İletişim
Proje hakkında daha fazla bilgi almak, öneride bulunmak veya katkı sağlamak isterseniz bizimle iletişime geçebilirsiniz:

Takım İletişim Sorumlusu: Huri Nisa İnsan
E-Posta (danışman): valuntas@gmail.com
LinkedIn bağlantılarımız ve GitHub repo linki, paylaşımlarımızda yer almaktadır.
Açık kaynak geliştirici topluluğuna katkı sağlamak isteyenler için repomuz açıktır.
✅ Katkı ve Destek
Proje açık kaynak olarak geliştirilmiştir. Kodları inceleyebilir, yıldızlayabilir veya fork ederek katkı sunabilirsiniz. Özellikle öneri algoritmaları, arayüz tasarımı veya performans optimizasyonu konularında geliştirme yapmak isteyen geliştiricilere açığız.

🏁 Sonuç
Bu proje, kullanıcıların dijital içerik platformlarında daha keyifli, zaman kazandıran ve kişisel ilgi alanlarına göre şekillenen bir deneyim yaşamalarını sağlamak amacıyla tasarlanmıştır. Takım olarak modern yazılım mühendisliği süreçlerine uygun biçimde ilerleyerek görev paylaşımı, dokümantasyon, test ve versiyon kontrol adımlarını dikkatle uyguladık.

📌 Bu proje, Bursa Teknik Üniversitesi Bilgisayar Mühendisliği "BLM0324 Yazılım Mühendisliği" dersi kapsamında 2025 Bahar döneminde geliştirilmiştir.
