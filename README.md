🏢 Yurt Yönetim Sistemi

Bu proje, Yazılım Mühendisliği – Yazılım Mimarisi ve Tasarımı dersi kapsamında geliştirdiğim kapsamlı bir Yurt Yönetim Sistemidir.

👩‍💻 Proje Ekibi

Proje geliştirme sürecinde yer alan ekip üyeleri:
	•	Aylin Öztürk – [AylinOztrk](https://github.com/AylinOztrk)
	•	Ayşegül Avcı – [avciaysegul](https://github.com/avciaysegul)

🎯 Projenin Amacı ve Özellikleri

Bu sistemin amacı, üniversite yurtlarında kullanılan kayıt, oda ve izin süreçlerini dijital ortamda yönetilebilir hale getirmektir.

🔑 Yönetici Paneli
	•	Öğrenci kaydı ekleme ve silme
	•	Oda doluluk durumlarını görüntüleme
	•	Öğrencilerden gelen izin taleplerini onaylama veya reddetme

🎓 Öğrenci Paneli
	•	Kendi profil bilgilerini görüntüleme
	•	Oda arkadaşlarını görme
	•	İzin talebi oluşturma ve talep durumunu takip etme

🗄 Veritabanı Entegrasyonu
	•	Tüm veriler MySQL veritabanında güvenli bir şekilde saklanmaktadır.

🛠 Kullanılan Teknolojiler ve Mimari
	•	Programlama Dili: Java
	•	Swing & AWT arayüz kütüphaneleri
	•	Veritabanı: MySQL
	•	IDE: IntelliJ IDEA

📐 Kullanılan Tasarım Desenleri (Design Patterns)
	•	Singleton: Veritabanı bağlantısının tek bir nesne üzerinden yönetilmesi
	•	Factory: Kullanıcı nesnelerinin (Öğrenci / Personel) dinamik olarak oluşturulması
	•	Observer: İzin durumu değişikliklerinin ilgili taraflara bildirilmesi
	•	Facade: Karmaşık alt sistemlerin tek bir arayüz üzerinden yönetilmesi

⚙ Kurulum ve Çalıştırma 

Projeyi kendi bilgisayarınızda çalıştırmak için aşağıdaki adımları izleyebilirsiniz:
	1.	Veritabanı Kurulumu
Proje içerisindeki veritabani.sql dosyasını MySQL Workbench kullanarak import ediniz.
	2.	Veritabanı Bağlantı Ayarı
src/com/yurt/db/DBConnection.java dosyasında yer alan veritabanı şifresini kendi yerel MySQL şifrenizle güncelleyiniz.
	3.	Uygulamayı Başlatma
Main.java dosyasını çalıştırarak giriş ekranına ulaşabilirsiniz.

🔐 Örnek Giriş Bilgileri
	•	Yönetici Girişi
	•	TC: 999
	•	Şifre: 1234
	•	Öğrenci Girişi
	•	TC: 111
	•	Şifre: 1234
