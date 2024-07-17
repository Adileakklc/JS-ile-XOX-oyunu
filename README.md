# XOX Oyunu

Bu proje, klasik XOX (Tic-Tac-Toe) oyununu içerir. Oyuncular bilgisayara karşı oynar ve ek olarak, beraberlik durumunda taş-kağıt-makas oyunu oynayarak kazanan belirlenir.

## Özellikler
- Kullanıcı dostu arayüz
- Oyuncu ve bilgisayar arasında XOX oyunu
- Beraberlik durumunda taş-kağıt-makas oyunu
- Skor takibi
- Renkli ve görsel açıdan çekici tasarım

## Kurulum
1. Bu projeyi bilgisayarınıza klonlayın:
   ```bash
   git clone https://github.com/Adileakklc/xox-oyunu.git
   ```
2. Proje dizinine gidin:
   ```bash
   cd xox-oyunu
   ```
3. `index.html` dosyasını bir tarayıcıda açın.

## Kullanım
1. **Oyunu Başlatma**: "BAŞLA" butonuna tıklayarak oyunu başlatın.
2. **Hamle Yapma**: Sıradaki oyuncu belirtilen hücrelere tıklayarak hamle yapar. Kullanıcı `O` harfiyle, bilgisayar ise `X` harfiyle oynar.
3. **Skor Takibi**: Oyun sonunda skorlar otomatik olarak güncellenir. Skor tablosu, kullanıcı ve bilgisayarın kazandığı oyunları ve beraberlikleri gösterir.

## Oyun Kuralları
- **XOX Oyunu**: 3x3 ızgara üzerinde oynanır. Oyuncular sırayla hücrelere `X` veya `O` koyar. Aynı harften üç hücreyi yatay, dikey veya çapraz bir şekilde ilk tamamlayan kazanır.
- **Taş-Kağıt-Makas Oyunu**: XOX oyunu berabere biterse, taş-kağıt-makas oyunu oynanır. Bilgisayar rastgele bir seçim yapar ve kullanıcıdan seçim yapması istenir. Kazanan belirlenir ve skor güncellenir.
