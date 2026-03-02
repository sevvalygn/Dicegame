# World Series of Dice

Basit zar oyunu: **Player 1 (siz)** vs **Player 2 (Bilgisayar)**. Her el tek zar atılır; yüksek atan kazanır.

**Amaç:** Kazanmak.

---

## Özellikler

- **Player 1:** Kullanıcı. Üstteki alandan kendi kullanıcı adınızı güncelleyebilirsiniz; etiket anında güncellenir.
- **Player 2:** Bilgisayar (sabit).
- **Zar at:** Turkuaz yuvarlak butona (shuffle ikonu) basınca her iki zar da yaklaşık **3 saniye** boyunca rastgele yüz değiştirir, ardından nihai sonuç ekranda gösterilir.
- **Sonuçlar:**
  - **Draw! 🤝** — Berabere
  - **Player 1 Wins! 🏆** — Siz kazandınız
  - **Player 2 Wins! 😔** — Bilgisayar kazandı
- Buton, sonuç geldikten sonra tekrar kullanılabilir (Tekrar at).

---

## Arayüz

- Koyu gri arka plan
- El yazısı tarzı font (Caveat) ile oyuncu isimleri ve sonuç metni
- Zar görselleri: kırmızı zarlar, `assets/` klasöründeki dice1.png–dice6.png
- Alt bilgi: www Dice🎲e Game .com

---

## Dosya yapısı

```
world-series-of-dice/
├── index.html      # Oyun sayfası (HTML, CSS, JS)
├── README.md       # Bu dosya
└── assets/
    ├── dice1.png   # Zar yüzü 1
    ├── dice2.png
    ├── dice3.png
    ├── dice4.png
    ├── dice5.png
    └── dice6.png   # Zar yüzü 6
```

---

## Çalıştırma

`index.html` dosyasını tarayıcıda doğrudan açabilirsiniz.

Yerel sunucu ile açmak isterseniz:

```bash
cd world-series-of-dice
npx serve .
# veya
python3 -m http.server 8080
```

Ardından tarayıcıda `http://localhost:3000` veya `http://localhost:8080` adresine gidin.

---

## Teknolojiler

- HTML5, CSS3, Vanilla JavaScript
- Zar görselleri: proje içi PNG (assets/)
- Google Fonts: Caveat (el yazısı etiketler ve sonuç)

---

Bol kazançlar.
