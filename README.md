# 🏠 Akıllı Temizlik Takipçisi (Simple Clean Tracker)

Bu uygulama, özellikle **unutkanlık yaşayan** veya **yoğun tempo** nedeniyle ev işlerini takip etmekte zorlanan bireyler için tasarlanmış, minimal bir dijital temizlik ajandasıdır. Karmaşık listeler yerine, "en son ne zaman yapıldığına" odaklanarak zihinsel yükünüzü hafifletir.

## ✨ Neden Bu Uygulamayı Kullanmalısınız?

Çoğu temizlik uygulaması size "bugün şunu yap" diye baskı yapar. Ancak bu uygulama size **"en son ne zaman yaptığınızı"** hatırlatır. Böylece:

* "Yerleri dün mü silmiştim?" sorusu ortadan kalkar.
* Gereksiz yere üst üste temizlik yapmazsınız.
* Çok uzun süre ihmal edilen alanları bir bakışta görürsünüz.

---

## 🛠 Temel Özellikler

* **Zaman Sayacı:** Her görev için son tamamlanma tarihini tutar ve üzerinden geçen zamanı (saat veya gün olarak) hesaplar.
* **Kategorize Görünüm:** Süpürme, toz alma, mutfak bakımı gibi işleri bölümlere ayırır.
* **Kalıcı Hafıza:** `localStorage` teknolojisi sayesinde tarayıcıyı kapatsanız veya bilgisayarı yeniden başlatsanız bile verileriniz kaybolmaz.
* **Tek Tıkla Güncelleme:** Bir işi bitirdiğinizde "Tamamladım" butonuna basmanız yeterlidir; sistem zamanı o an sıfırlar.

---

## 📋 Kullanım Kılavuzu

1. **Dosyayı Açın:** Size verilen HTML kodunu bir metin belgesine yapıştırın ve adını `temizlik.html` yaparak kaydedin. Ardından herhangi bir internet tarayıcısıyla açın.
2. **Takibe Başlayın:** Listede bulunan temizlik görevlerini inceleyin.
3. **Kayıt Tutun:** Bir işi (örneğin: Yerleri Süpürme) bitirdiğiniz anda yanındaki **"Tamamladım"** butonuna basın.
4. **Kontrol Edin:** Uygulama, o işin altına "Bugün yapıldı (X saat önce)" veya "X gün önce yapıldı" notunu düşecektir.

---

## 🏗 Teknik Detaylar

Uygulama tamamen **istemci taraflı (client-side)** çalışır. Bu ne anlama gelir?

* **Gizlilik:** Verileriniz hiçbir sunucuya gönderilmez, sadece sizin bilgisayarınızda saklanır.
* **Hız:** İnternet bağlantınız olmasa bile (dosya bilgisayarınızda olduğu sürece) çalışmaya devam eder.
* **Hafiflik:** Hiçbir kurulum gerektirmez.

---

## 🚀 Gelecek Planları (Sürüm 2.0 Önerileri)

Eğer bu temel sürüm size yardımcı olursa, şu özellikleri de ekleyebiliriz:

* **Renk Kodları:** 3 günden fazla süre geçmiş işlerin kırmızıya dönmesi.
* **Özel Görevler:** Kendi ev işlerinizi uygulamaya ekleme paneli.
* **Sesli Bildirim:** İşin zamanı geldiğinde küçük bir hatırlatıcı ses.



Bu dosyayı telefonunuzun ana ekranına kısayol olarak eklerseniz, tıpkı gerçek bir mobil uygulama gibi hızlıca erişebilirsiniz.

