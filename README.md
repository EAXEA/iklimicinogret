# İklim için Değişen ve Dönüştüren Öğretmenler — Web Sitesi

Statik bir web sitesidir. Sunucuya yükleme veya kurulum gerektirmez.

## Lokal'de açmak için

### En kolay yol
**`index.html` dosyasına çift tıklayın.** Tarayıcıda açılır.

> Tarayıcınız çevrimiçiyse Google Fonts ve daha güzel tipografi yüklenir.
> Çevrimdışıyken sistem fontları kullanılır — site yine sorunsuz çalışır.
> Tüm fotoğraflar, galeri kütüphaneleri (Swiper + PhotoSwipe) ve PDF zaten klasörün içinde.

### Eğer çift tıklamayla galeri çalışmazsa
Klasörün içindeyken bir terminal/komut istemi açın ve:

```
python3 -m http.server 8080
```

komutunu çalıştırın (Python 3 kurulu olmalı). Ardından tarayıcıda:

```
http://localhost:8080
```

adresini açın. Bu hâlde **tüm özellikler** (galeri, lightbox, animasyonlar) garantili çalışır.

## Klasör yapısı

```
iklim-ogretmenler-site/
├── index.html               ← Ana site
├── project.png              ← Proje logosu
├── odtu.png                 ← ODTÜ logosu
├── robots.txt
├── sitemap.xml
├── files/                   ← Tüm görseller, PDF, ekip fotoğrafları
│   ├── ogretmenelkitabi.pdf
│   ├── panel/               ← Atölye + program afişi fotoğrafları
│   ├── team/                ← Ekip portreleri
│   └── logos/
└── vendor/                  ← Galeri kütüphaneleri (Swiper, PhotoSwipe — lokal)
```

Modern tarayıcılarda (Chrome, Safari, Firefox, Edge — güncel sürümler) açılır.
