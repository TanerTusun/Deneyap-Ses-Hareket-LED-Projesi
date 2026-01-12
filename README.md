# 🔊🏃‍♂️ Akıllı Ses ve Hareket Algılama Sistemi
> Deneyap Kart 1a Tabanlı Otonom Aydınlatma Projesi

![Durum](https://img.shields.io/badge/Durum-Tamamlandı-success)
![Platform](https://img.shields.io/badge/Platform-Deneyap_Kart-blue)
![Dil](https://img.shields.io/badge/Kodlama-C%2B%2B%20%2F%20Arduino-orange)

## 📖 Proje Hakkında
Bu proje, çevre birimlerinden alınan analog ve dijital verilerin işlenmesi prensibine dayanan bir gömülü sistem uygulamasıdır. **Deneyap Kart 1a** mikrodenetleyicisi merkezli bu sistem, ortamdaki **ses seviyesini** ve **fiziksel hareketi** eş zamanlı olarak analiz eder.

Belirlenen eşik değerleri aşıldığında sistem otomatik olarak tetiklenerek görsel uyarıcıyı (LED) devreye sokar. Bu prototip, akıllı ev sistemleri ve güvenlik otomasyonları için temel bir model oluşturmaktadır.

## 🛠️ Teknik Donanım ve Bileşenler
Projede aşağıdaki Deneyap ekosistemi ve elektronik bileşenler kullanılmıştır:

* **Ana Kontrolcü:** Deneyap Kart 1a
* **Sensör 1:** Deneyap Mikrofon Modülü (Ses Algılama)
* **Sensör 2:** Deneyap Hareket Algılama Sensörü (PIR)
* **Çıktı Birimi:** LED ve Direnç
* **Bağlantı:** MB102 Breadboard ve Jumper Kablolar

## ⚙️ Nasıl Çalışır?
1.  **Veri Toplama:** Mikrofon ortamdaki desibel değişimlerini, PIR sensörü ise kızılötesi hareket değişimlerini sürekli olarak tarar.
2.  **İşleme:** Sensörlerden gelen veriler Deneyap Kart işlemcisinde, yazdığımız algoritma ile analiz edilir.
3.  **Tetikleme:** Eğer ortamda bir hareket VEYA belirli seviyenin üzerinde bir ses varsa, sistem `HIGH` sinyali göndererek LED'i aktif eder.

## 👨‍💻 Proje Ekibi (Geliştiriciler)
Bu proje aşağıdaki ekip tarafından tasarlanmış ve kodlanmıştır:
* **Taner TUSUN** 
* **Büşra KERÇEK** 

---
*Bu proje [Bilecik Şeyh Edebali Üniversitesi/Bilgisayar Donanımı ve İşletm Sistemleri/Dr. Öğretim Üyesi Hüseyin PARMAKASIZ] kapsamında geliştirilmiştir. © 2026*

