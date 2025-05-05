# DreamClass

**YZTA-JAM - Grup 27** tarafından geliştirilen bu proje, öğrenciler için yapay zeka destekli kişiselleştirilmiş ve etkileşimli ders deneyimleri sunan bir eğitim platformudur.
**DreamClass**, Google Gemini API ile entegre çalışarak hikâyeleştirme, içerik üretimi ve quiz gibi çeşitli eğitim materyalleri üretmektedir.

> **Not:** Projenin son sürümü `master` branch'inde mevcuttur.

---

## 🚀 Özellikler

* 🎨 Hayal gücüne dayalı öğrenme deneyimi
* 🤖 Google Gemini destekli içerik üretimi
* 🧐 Hikaye tabanlı ders içerikleri
* 📝 Otomatik quiz oluşturma
* ⚙️ Kişiselleştirilebilir yapı

---

## 📁 .env Dosyası Kurulumu

Projenin çalışabilmesi için kök dizine bir **`.env`** dosyası oluşturmanız gerekmektedir. Aşağıdaki formatı kullanarak gerekli bilgileri doldurun:

```env
GOOGLE_API_KEY=your_api_key_here
GOOGLE_CLIENT_ID=your_client_id_here
GOOGLE_CLIENT_SECRET=your_client_secret_here
API_RESTRICTIONS=true
ALLOWED_DOMAINS=localhost:5000,127.0.0.1:5000,localhost,127.0.0.1
ALLOWED_API=Generative Language API
ALLOWED_IPS=127.0.0.1,localhost
DEBUG=True
PORT=5000
HOST=0.0.0.0
```

---


## 📜 Lisans

Bu proje [MIT Lisansı](LICENSE) ile lisanslanmıştır.
