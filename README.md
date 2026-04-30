# 🏥 Acil Triyaj Arcade

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML5](https://img.shields.io/badge/HTML5-Canvas-orange)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![Retro Style](https://img.shields.io/badge/Style-Retro--Arcade-red)](#)

**Acil Triyaj Arcade**, acil servis triyaj mantığını Street Fighter tarzı retro arcade mekanikleriyle birleştiren bir web uygulamasıdır. Uzm. Dr. Yasin Yıldız tarafından geliştirilen bu oyun, hem reflekslerinizi test eder hem de kaotik bir acil servis atmosferinde doğru karar verme yetinizi ölçer.

---

## 🚀 Özellikler

- **🕹️ Klasik Arcade Deneyimi:** Street Fighter tarzı başlıklar, 8-bit ses efektleri ve piksel sanatıyla tasarlanmış grafikler.
- **⚕️ Triyaj Mekaniği:** Hastaları renk kategorilerine göre (Yeşil, Sarı, Kırmızı) sedyeye toplayarak puan kazanın.
- **⚠️ Dinamik Zorluk:** Oyun her 60 saniyede bir hızını %10 artırır. Survival modunda ne kadar dayanabilirsiniz?
- **💀 Ex (Siyah) Hasta Riski:** Renkli hastalar her an siyaha dönüşebilir! Yakalarsanız puan kaybedersiniz.
- **📱 Mobil & PC Uyumlu:** Bilgisayarda klavye (A-D / Ok Tuşları), mobilde hassas dokunmatik kontrol.
- **📈 Skor Tablosu:** Tarayıcı kapansa bile en yüksek 3 skorunuzu hatırlayan LocalStorage entegrasyonu.
- **🎵 Ses Yönetimi:** Web Audio API ile sentezlenen 8-bit fon müziği ve efektler için ayrı kontroller.

---

## 🎮 Nasıl Oynanır?

1. **Oyunu Başlatın:** "BAŞLA" butonuna basarak acil servis kaosuna giriş yapın.
2. **Hastaları Yakalayın:** Sedyeyi sağa sola hareket ettirerek düşen hastaları toplayın.
   - **Yeşil:** +5 Puan
   - **Sarı:** +10 Puan
   - **Kırmızı:** +20 Puan
   - **Siyah (Ex):** -15 Puan (Dikkat! Renkliler aniden siyaha dönebilir).
3. **Zorluk Modları:** KOLAY, ORTA ve ZOR modları arasından seçiminizi yapın.
4. **Paylaşın:** Oyun bittiğinde skor kartınızı oluşturun ve sosyal medyada paylaşın.

---

## 🛠️ Teknik Detaylar

Oyun tamamen modern web teknolojileri kullanılarak, harici bir kütüphane bağımlılığı olmadan geliştirilmiştir:

- **HTML5 Canvas:** Akıcı 60 FPS animasyonlar için.
- **CSS3:** Retro atmosfer, Street Fighter tarzı fontlar ve kaotik arka plan düzeni.
- **JavaScript (Vanilla):** Oyun motoru, çarpışma algılama ve hız artış mantığı.
- **Web Audio API:** 8-bit retro seslerin anlık sentezlenmesi için.
- **Web Share API:** Skor kartlarının görsel olarak paylaşılabilmesi için.

---

## 📂 Kurulum

Projeyi yerelinizde çalıştırmak için:

1. Bu repository'yi klonlayın:
   ```bash
   git clone [https://github.com/kullaniciadin/triyaj-arcade.git](https://github.com/kullaniciadin/triyaj-arcade.git)

2. Proje klasörüne gidin:
   ```bash
   cd triyaj-arcade

3. index.html dosyasını herhangi bir modern tarayıcıda açın.

👨‍⚕️ Geliştirici
Uzm. Dr. Yasin Yıldız

© 2026 Tüm Hakları Saklıdır.

📄 Lisans
Bu proje MIT Lisansı altında lisanslanmıştır. Detaylar için LICENSE dosyasına bakınız.
