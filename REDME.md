Öğrenci Bilgi Sistemi

Ad Soyad : SIDAHMED MOHAMED BEWBE
Numara:2411084715

1. Projenin Amacı (Neden bu proje?)

Bu proje neden yapıldı?
Öğrencilerin ders bilgilerini, notlarını ve genel öğrenci verilerini merkezi bir sistemde toplamak için yapıldı. Manuel işlem yapılan sistemlerde yaşanan karışıklıkları ve zaman kayıplarını azaltmak amaçlandı.

Hangi problemi çözüyor?

Öğrenci bilgilerine hızlı erişim

Notların dijital takibi

Yönetim, öğretmen ve öğrenciler arasında bilgi paylaşımı

Kayıt işlemlerinde hata oranını azaltma


Gerçek dünyadaki karşılığı var mı?
Evet, üniversitelerde ve okullarda kullanılan öğrenci otomasyon sistemlerinin dijital versiyonudur. Gerçek hayatta birçok kurum benzer sistemler kullanmaktadır.


---

2. Projenin Kapsamı ve Özellikleri

Sistem ne yapabiliyor?

Öğrenci girişi ve öğretmen/admin girişi

Yeni öğrenci kaydı

Ders ve not bilgisi ekleme

Öğrenci bilgisi arama

Not güncelleme ve silme


Sistem ne yapamıyor?

Canlı mesajlaşma veya bildirim sistemi yok

Çok kullanıcılı eş zamanlı işlem desteği henüz yok

Detaylı kullanıcı yetkilendirme sistemi yok


Kapsam dışında neler kaldı? Neden?

Mobil uygulama kısmı yapılmadı (zaman yetersizliği)

Çoklu dil desteği eklenmedi (öncelik temel işlevlerdi)

Gelişmiş analiz raporları şimdilik dışında bırakıldı



---

3. Kullanılan Teknolojiler

Frontend: HTML, CSS, JavaScript, Bootstrap

Backend: Python + Flask

Veritabanı: SQLite

Ekstra Araçlar: Postman (API testleri için), GitHub (versiyon kontrolü)


Tercih sebebi:
Flask hafif ve öğrenmesi kolay bir framework olduğu için tercih edildi. SQLite küçük projeler için uygun ve kurulumu kolay. Bootstrap sayesinde hızlıca responsive tasarım sağlandı.


---

4. Kurulum ve Çalıştırma Talimatları

Evet, başka bir kişi kolayca projeyi çalıştırabilir.

Adımlar:

1. Python 3.x kurulu olmalı


2. git clone < https://github.com/sidi96056/int.git > komutu ile proje indirilmeli


3. Terminalden proje klasörüne girilmeli


4. Gerekli kütüphaneler: pip install -r requirements.txt


5. Uygulama başlatma: python app.py


6. Tarayıcıdan: http://127.0.0.1:5000




---

5. Dosya Yapısı ve Açıklamaları

/ogrenci-bilgi-sistemi
│
├── app.py                → Ana uygulama dosyası
├── templates/            → HTML dosyaları
│   ├── login.html
│   ├── dashboard.html
│  
├── static/               → CSS/JS dosyaları
├── data.db           → SQLite veritabanı
├── requirements.txt      → Gerekli kütüphaneler listesi
└── README.md             → Kurulum ve açıklamalar


6. Ekran Görselleri :

Video: https://drive.google.com/file/d/1APS9YQCMxFSlCkLUJcUmy8hRjTIK3nQQ/view?usp=sharing




7. Zorluklar ve Öğrenilenler

Karşılaşılan Sorunlar:

Flask ile form verisi alma hataları

Veritabanı bağlantı sorunları

Bootstrap ile responsive tasarım uyumu


Çözüm yolları:

Flask belgeleri ve Stack Overflow kaynakları kullanıldı

Basit hataları deneme-yanılma ile çözdüm

Bootstrap için örnek tasarımlar incelendi


Öğrenilenler:

Flask ile web uygulama geliştirme

CRUD işlemleri uygulama

Proje planlaması yapmanın önemi



---

8. Geliştirilebilir Yönler

Vaktim olsaydı:

Kullanıcı yetkilendirme ve şifre sıfırlama sistemi eklerdim

Grafiksel not analizleri eklerdim

RESTful API desteği ile mobil uygulama bağlantısı kurardım


Gelecek fikirler:

Notlara göre başarı grafiği

Öğrenciye özel bildirimler

PDF çıktısı alma



---


