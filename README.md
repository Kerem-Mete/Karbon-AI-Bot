# ♻️ Karbon Ayak İzi Hesaplayıcı Discord Botu

Merhaba! Bu bot, kişisel karbon ayak izinizi tahmin etmek için tasarlanmış bir Discord botudur.  
Kullanıcıların günlük alışkanlıklarına göre yıllık CO₂ salınımlarını hesaplar, verilerini kaydeder ve önceki verilerle kıyaslamalar yapar.  
İki dil desteklenir: **Türkçe 🇹🇷** ve **İngilizce 🇬🇧**

---

## 🚀 Özellikler

- 📊 Günlük araba, elektrik, su ve et tüketimini sorar  
- 🌍 Yıllık karbon ayak izinizi hesaplar  
- 📚 Önceki verilerinizi görüntüler  
- 🔁 Son iki kaydı karşılaştırır  
- 🧹 Tüm verileri temizleyebilir  
- 🌐 Dil seçeneği: `!dil en` veya `!dil tr`

---

## 📦 Kurulum

1. Bu projeyi klonla:
    ```bash
    git clone https://github.com/kullaniciadi/karbon-bot.git
    cd karbon-bot
    ```

2. Gereksinimleri yükle:
    ```bash
    pip install -r requirements.txt
    ```

3. `.env` dosyası oluştur ve Discord bot token’ını gir:
    ```
    DISCORD_BOT_TOKEN=senin_tokenin
    ```

4. Botu başlat:
    ```bash
    python bot.py
    ```

---

## 🛠️ Kullanılan Teknolojiler

- Python 🐍
- discord.py 📡
- Basit veritabanı olarak Python sözlükleri 📁

---

## 💬 Komutlar

| Komut         | Açıklama                                                                 |
|---------------|--------------------------------------------------------------------------|
| `!tanitim`    | Botun yaratıcısını tanıtır 👤                                             |
| `!dil en/tr`  | Bot dilini değiştirir 🌐                                                 |
| `!hesapla`    | Günlük tüketim bilgilerinizi alır ve yıllık karbon ayak izinizi hesaplar 🔍 |
| `!geçmiş`     | Geçmişteki kayıtlarınızı listeler 📜                                      |
| `!karsilastir`| Son iki kayıt arasında karşılaştırma yapar ⚖️                             |
| `!temizle`    | Tüm kayıtlarınızı siler 🧹
