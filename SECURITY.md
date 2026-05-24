1. Amaç ve Kapsam
Bu Bilgi Güvenliği Politikası, Harezmi Projesi bünyesinde üretilen, işlenen ve saklanan tüm dijital ve fiziksel varlıkların gizliliğini, bütünlüğünü ve erişilebilirliğini korumak amacıyla oluşturulmuştur. Bu politika; tüm çalışanları, yüklenicileri, danışmanları ve üçüncü taraf hizmet sağlayıcılarını kapsamaktadır.

2. Temel İlkeler
Güvenlik stratejimiz üç ana sac ayağı (CIA Triad) üzerine kuruludur:

Gizlilik (Confidentiality): Bilgilerin yetkisiz kişilerin eline geçmesinin engellenmesi.

Bütünlük (Integrity): Bilgilerin yetkisiz kişilerce değiştirilmesinin veya tahrif edilmesinin önlenmesi.

Erişilebilirllik (Availability): Yetkili kullanıcıların ihtiyaç duydukları an bilgiye ve sistemlere kesintisiz ulaşabilmesi.

3. Veri Güvenliği ve Şifreleme
Süreç içi (In-Transit) Veri: Kullanıcılar ile sunucularımız arasındaki tüm trafik TLS (HTTPS) protokolü kullanılarak en güncel şifreleme standartlarıyla korunur.

Saklanan (At-Rest) Veri: Veritabanlarında tutulan hassas veriler (şifreler, kişisel veriler vb.) güçlü kriptografik algoritmalar (Örn: AES-256, SHA-256) kullanılarak şifrelenir. Kullanıcı şifreleri asla düz metin (plain-text) olarak saklanmaz.

4. Erişim ve Kimlik Yönetimi
En Az Yetki İlkesi (Principle of Least Privilege): Çalışanlara ve sistem rollerine, yalnızca işlerini yapabilmeleri için ihtiyaç duydukları minimum yetki tanımlanır.

Güçlü Parola Politikası: Tüm sistem girişlerinde karmaşık (büyük/küçük harf, rakam ve özel karakter içeren) ve düzenli olarak değiştirilen parolalar zorunludur.

Çok Faktörlü Kimlik Doğrulama (MFA): Kritik yönetim panellerine ve sunucu altyapılarına erişimde MFA kullanımı zorunludur.

5. Uygulama ve Yazılım Geliştirme Güvenliği
Geliştirilen tüm yazılımlarda OWASP Top 10 (en yaygın web uygulaması güvenlik riskleri) standartları gözetilir.

SQL Injection, Cross-Site Scripting (XSS) ve CSRF gibi saldırılara karşı girdi doğrulama (input validation) ve çıktı kodlama (output encoding) süreçleri uygulanır.

Üretim (Production) ortamına alınmadan önce tüm kodlar güvenlik testlerinden geçirilir.

6. Sızma Testleri ve Güvenlik Açığı Yönetimi
Sistemlerimiz üzerinde yılda en az bir kez bağımsız siber güvenlik firmaları tarafından Sızma Testi (Penetration Test) gerçekleştirilir.

Kritik güvenlik yamaları ve güncellemeler, sistem açıklarına karşı düzenli olarak takip edilir ve sistemlere hızla uygulanır.

7. Fiziksel ve Çevresel Güvenlik
Sunucu altyapılarımızın barındırıldığı veri merkezleri (Data Center), biyometrik geçiş sistemleri, 7/24 kamera takibi ve yangın/enerji kesintisi korumalarına sahip profesyonel sağlayıcılardan (Örn: AWS, Google Cloud, Azure vb.) seçilir.

8. Güvenlik İhlal Bildirimleri
Herhangi bir güvenlik ihlali şüphesi durumunda, durum derhal Güvenlik Ekibine rapor edilir. Kullanıcı verilerini etkileyen olası bir siber saldırı veya veri sızıntısı durumunda, yasal mevzuatlar (KVKK/GDPR) uyarınca etkilenen taraflara ve resmi kurumlara yasal süresi içinde bildirim yapılır.

9. İletişim ve Güvenlik Açığı Bildirimi (Vulnerability Disclosure)
Sistemlerimizde bir güvenlik açığı bulduğunuzu düşünüyorsanız, bunu kötü niyetli kullanımlardan önce bize bildirmenizi rica ederiz. Güvenlik açıklarını bildirmek için lütfen aşağıdaki e-posta adresini kullanın:

📬 E-posta: security@1Nyse1.github.com

10. Politika İncelemesi ve Güncelleme
Bu politika belgesi, gelişen teknoloji ve değişen tehdit unsurları göz önünde bulundurularak yılda en az bir kez gözden geçirilir ve güncellenir.

Yürürlük Tarihi: 24.05.2026

Versiyon: 1.0
