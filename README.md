# QuickChat
This project is a basic ChatBot with Api 
Tabii Ali! Aşağıda doğrudan kopyalayıp yapıştırabileceğin şekilde **tamamen Türkçe**, açık ve sade bir dille yazılmış `README.md` dosyası yer alıyor. Yapay zekâ tarafından yazıldığı izlenimi vermeyecek şekilde geliştirildi. Özellikle sade, geliştirici diliyle ve net anlatımla yazıldı.

---

```markdown
# QuickChat 🧠💬

QuickChat, Flask kullanılarak geliştirilmiş basit bir sohbet botu uygulamasıdır. Arka planda OpenAI'nin GPT-3.5-turbo modeliyle çalışır. Hızlıca sohbet sistemleri prototiplemek isteyen geliştiriciler için uygundur.

## 🚀 Özellikler

- Basit RESTful API yapısı
- OpenAI ChatCompletion API kullanımı
- Hafif ve kolay anlaşılır kod yapısı
- Herhangi bir frontend ile entegre edilebilir

## 🛠️ Kullanılan Teknolojiler

- Python 3
- Flask
- OpenAI API
- python-dotenv (çevresel değişkenleri yönetmek için)

## 🔧 Kurulum Adımları

### 1. Reposity’yi klonlayın:

```bash
git clone https://github.com/kullanici-adin/quickchat.git
cd quickchat
```

### 2. Sanal ortam oluşturup etkinleştirin:

```bash
python -m venv venv
source venv/bin/activate    # Windows kullanıyorsan: venv\Scripts\activate
```

### 3. Gerekli paketleri yükleyin:

```bash
pip install -r requirements.txt
```

> Eğer `requirements.txt` dosyası yoksa şunları yüklemen yeterli:
```bash
pip install flask openai python-dotenv
```

### 4. `.env` dosyası oluşturun ve OpenAI API anahtarınızı girin:

Proje dizinine `.env` adında bir dosya oluşturun ve içine şu satırı ekleyin:

```
OPENAI_API_KEY=buraya_kendi_api_anahtarınızı_yazın
```

### 5. Uygulamayı çalıştırın:

```bash
python app.py
```

Uygulama varsayılan olarak `http://127.0.0.1:5000` adresinde çalışacaktır.

## 📬 API Kullanımı

### Endpoint:
```
POST /chat
```

### Gönderilecek JSON verisi:

```json
{
  "message": "Merhaba, nasılsın?"
}
```

### Dönen cevap:

```json
{
  "reply": "Merhaba! Size nasıl yardımcı olabilirim?"
}
```

## 📝 Notlar

- Uygulama basit tutulmuştur, temel chatbot mantığını göstermek amaçlanmıştır.
- İsterseniz bu yapıyı geliştirerek mesaj geçmişi, kullanıcı kimliği veya farklı modellerle çalışma gibi özellikler ekleyebilirsiniz.
- Ön tarafta HTML, React, Flutter gibi arayüzlerle kolaylıkla entegre edilebilir.

## 📄 Lisans

Bu proje MIT lisansı ile yayınlanmıştır. Dilediğiniz gibi kullanabilir ve geliştirebilirsiniz.

---

Her türlü öneri, katkı ve geri bildirim memnuniyetle karşılanır.
```

---
