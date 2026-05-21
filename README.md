# Ayyıldız Çiçekçilik

Bu proje, Bartın merkezli çiçekçilik markası için tek sayfa statik web sitesidir.

## İçerik
- `index.html` — Web sitesinin ana sayfası, doğrudan tarayıcıda açılabilir.
- `ayyildiz-cicekcilik.html` — orijinal site sürümü ve kaynak HTML dosyası.
- `logo.png` — site logosu.
- `site-execution-plan.md` — proje ve yayınlama planı.

## Yayınlama
Bu siteyi hızlıca yayına almak için aşağıdaki adımları kullanabilirsiniz.

### 1. GitHub Pages
1. GitHub hesabı oluşturun veya giriş yapın.
2. Yeni bir depo oluşturun.
3. Bu klasörü yerel depo olarak taşıyın:
   ```powershell
   cd "c:\Users\FurkaN\Desktop\ayyıldız çiçekçilik"
   git remote add origin https://github.com/<kullanici>/<repo>.git
   git push -u origin main
   ```
4. GitHub depo ayarlarında `Pages` sekmesine gidin.
5. `Source` olarak `main` dalını seçin ve `root` dizini kullanın.

### 2. Netlify
1. Netlify hesabı oluşturun.
2. `New site from Git` seçeneğiyle GitHub depo bağlantısı kurun.
3. Deploy ayarlarında build komutu yoksa boş bırakın, yayımlanacak dizin `./` olarak kalsın.
4. Deploy tamamlandığında size verilen adresi kullanabilirsiniz.

### 3. Özel Domain Bağlama
- Domain satın aldıktan sonra DNS ayarlarında `A` kaydı veya `CNAME` kaydı ekleyin.
- GitHub Pages için repo ayarlarından `Custom domain` kısmına alan adını yazın.
- Netlify için `Domain management` bölümüne alan adını ekleyin.
- Çoğu servis SSL sertifikasını otomatik tanımlar.

## Notlar
- `index.html` dosyası doğrudan site kökünde kullanılmalıdır.
- Eğer farklı bir alan adı alırsanız, `CNAME` dosyası ekleyebilirsiniz:
  ```text
  example.com
  ```

## İletişim
- WhatsApp: https://wa.me/905533453040
- E-posta: ayyildizsongul50@gmail.com
