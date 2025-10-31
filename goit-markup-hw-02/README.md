# goit-markup-hw-02 — Starter repository

Bu repo GOIT Markup HW #02 için hazır bir şablon sağlar. İçinde "Our Portfolio" bölümü tamamlanmıştır.
**ÖNEMLİ:** Kendi önceki çalışmanızı `images/` klasörüne kopyalayın ve metinleri index.html içinde güncelleyin.

## İçerik
- `index.html` — ana sayfa (Our Portfolio bölümü dahil)
- `css/styles.css` — tüm stil kuralları burada
- `images/` — tüm görseller burada (jpg formatında)
- `.gitignore`

## Yapılacaklar (yerel adımlar)
1. Depoyu oluşturun / klonlayın:
   ```bash
   git init goit-markup-hw-02
   cd goit-markup-hw-02
   # veya uzak GitHub repo'sunu klonlayın:
   # git clone https://github.com/USERNAME/goit-markup-hw-02.git
   ```

2. Kendi önceki çalışmanızın dosyalarını buraya kopyalayın:
   ```bash
   cp -r /path/to/your/old-project/* ./
   # veya sadece görselleri koymak için:
   cp /path/to/old/images/*.jpg images/
   ```

3. Görselleri Squoosh ile optimize edin:
   - https://squoosh.app/ adresine gidin.
   - Görseli yükleyin, `MozJPEG` veya `WebP` seçin (ödev JPG istiyor — export JPG seçeneği) ve quality/resize ayarlarını yapın.
   - Export edin ve `images/` klasöründeki dosyaların üzerine yazın.

4. Kaynak kodu Prettier ile biçimlendirin (opsiyonel, ancak kriter A5 için gerekli):
   ```bash
   npm init -y
   npm install --save-dev prettier
   npx prettier --write "**/*.html" "css/**/*.css"
   ```

5. GitHub'a yükleme ve Pages kurulumu:
   ```bash
   git add .
   git commit -m "Initial: HW02 layout and portfolio section"
   # uzak repo ekle (GitHub'da repo oluşturup URL ile değiştirin)
   git remote add origin https://github.com/YOUR_USERNAME/goit-markup-hw-02.git
   git push -u origin main
   ```
   - GitHub'da repo > Settings > Pages bölümünden `main` branch ve `/ (root)` seçip GitHub Pages'i etkinleştirin.
   - Etkinleştikten sonra ortaya çıkan canlı sayfa URL'sini kopyalayın.

6. GitHub repo'sunun About bölümüne canlı sayfa bağlantısını ekleyin:
   - GitHub repo sayfasına gidin > sağda `About` bölümünü bulun > `Website` alanına Pages URL'sini yapıştırın.

## Kontrol listesi (mentor kriterlerine göre)
- A1: `images/` klasörü -> **var**
- A2: `css/` klasörü -> **var**
- A3: `css/styles.css` -> **var**
- B1: Our Portfolio -> `index.html` içinde -> **var**
- B6: `<img>` etiketlerinde `width` niteliği -> **var**
- Görseller jpg formatında dışa aktarılmıştır -> örnek görseller `.jpg` olarak eklendi.

## Notlar
- Lütfen kendi içerik/görsellerinizi `images/` klasörüne koyun.
- Eğer benzeri bir kontrol listesi hatası görürseniz, bu README içindeki adımları uygulayarak düzeltebilirsiniz.
