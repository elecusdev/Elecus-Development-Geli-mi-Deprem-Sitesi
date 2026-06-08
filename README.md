# DepremTakip - Canlı Deprem Bilgi Sistemi

**DepremTakip**, Türkiye ve çevresindeki deprem verilerini gerçek zamanlı olarak takip etmenizi sağlayan bir web uygulamasıdır. Kandilli Rasathanesi verileriyle çalışan bu sistem, kullanıcı dostu arayüzü ve zengin özellikleriyle tüm deprem bilgilerine kolayca erişmenizi sağlar.

## 🌐 Demo

Canlı Demo: [deprem-takip.vercel.app](https://deprem-bilgii.vercel.app/)

## 🌟 Özellikler

### 📊 Canlı Deprem Haritası
- Gerçek zamanlı deprem lokasyonlarını interaktif harita üzerinde görüntüleme
- Deprem büyüklüğüne göre renklendirilmiş işaretçiler
- Fay hatları katmanıyla kritik bölgeleri inceleme
- Deprem detaylarını gösteren pop-up bilgi kutuları
- Haritada deprem noktalarına tek tıkla odaklanma

### 📋 Detaylı Deprem Listesi
- Son depremlerin kronolojik sıralaması
- Büyüklük, derinlik, konum ve zaman bilgileri
- Deprem büyüklüğüne göre renk kodlaması
- "Daha Fazla Göster" özelliği ile daha fazla deprem verisi yükleme

### 🔍 Gelişmiş Filtreleme
- Büyüklüğe göre deprem filtreleme
- Konum bazlı arama yapabilme
- Önemli depremleri (4.0+) ayrı sekmede görüntüleme
- Filtrelerin kullanıcı tercihi olarak kaydedilmesi

### 📈 İstatistikler ve Analizler
- Son 24 saat, 7 gün ve 30 günlük deprem istatistikleri
- Toplam deprem sayısı ve büyüklük kategorilerine göre dağılım
- En büyük depremin detayları
- Deprem büyüklüğü dağılımını gösteren grafikler

### 🔔 Bildirim Sistemi
- Önemli depremler (4.0+) için bildirim seçeneği
- Tarayıcı bildirimleri ile anında haberdar olma
- Bildirim geçmişini görüntüleme
- Bildirim tercihlerini kaydetme

## 🧩 Nasıl Kullanılır?

### Deprem Haritası
1. Ana sayfadaki haritada tüm depremler görüntülenir
2. Depremlerin büyüklüğüne göre renk kodlaması:
   - 🔴 **Kırmızı**: 5.0 ve üzeri depremler
   - 🟡 **Sarı**: 4.0-4.9 arası depremler
   - 🔵 **Mavi**: 3.0-3.9 arası depremler
   - ⚪ **Gri**: 3.0'dan küçük depremler
3. Fay hatları katmanını açıp kapatabilirsiniz
4. Deprem işaretçilerine tıklayarak detaylı bilgilere erişebilirsiniz

### Filtreleme
1. Büyüklük filtresine minimum deprem büyüklüğünü girin
2. Konum filtresine aramak istediğiniz bölge adını yazın
3. "Uygula" butonuna tıklayın veya Enter tuşuna basın
4. Filtreleri temizlemek için "Temizle" butonunu kullanın

### Bildirimler
1. Sağ üst köşedeki "Bildirimler" butonuna tıklayın
2. Tarayıcı izinlerini onaylayın
3. Artık 4.0 ve üzeri depremler olduğunda anında bildirim alacaksınız
4. Bildirimlerinizi sayfanın sağ tarafındaki "Son Bildirimler" panelinde görebilirsiniz

### İstatistikler
1. Sağ taraftaki "Deprem İstatistikleri" kartında bulunan sekmeleri kullanarak farklı zaman dilimlerindeki istatistikleri görüntüleyin
2. Grafikte deprem büyüklüğü dağılımını inceleyebilirsiniz

## ⚙️ Yerel Geliştirme

Projeyi kendi bilgisayarınızda çalıştırmak için:

1. Repoyu klonlayın:
   ```bash
   git clone https://github.com/akiracik/deprem-bilgi.git
   cd deprem-takip
   ```

2. Bağımlılıkları yükleyin:
   ```bash
   npm install
   ```

3. Geliştirme sunucusunu başlatın:
   ```bash
   npm run dev
   ```

---

Depremler hakkında bilgi sahibi olmak, afetlere karşı hazırlıklı olmak için önemli bir adımdır. Güvende kalın! 🌍🏠

[![Discord Banner](https://api.weblutions.com/discord/invite/codeworld/)](https://discord.gg/codeworld)
