# ChatBot

Modern ve kullanıcı dostu bir arayüze sahip, Google Gemini API destekli C# WinForms sohbet uygulaması.


## Özellikler

*   **Google Gemini Entegrasyonu:** Güçlü AI modelleriyle akıllı sohbet deneyimi.
*   **Modern Arayüz:** Yuvarlatılmış köşeler, şık sohbet baloncukları ve temiz tasarım.
*   **Markdown Desteği:** Bot yanıtlarında kalın, italik ve diğer formatlamaları görüntüleme.
*   **Sohbet Geçmişi:** Bağlamı koruyan akıllı sohbet hafızası.
*   **Güvenli Yapılandırma:** API anahtarları kaynak kodundan ayrı tutulur.

## Kurulum ve Kullanım

### Gereksinimler

*   .NET Framework 4.8
*   Visual Studio 2019 veya daha yenisi

### Yapılandırma

Bu proje Google Gemini API kullanmaktadır. Çalıştırmadan önce bir API anahtarı almanız gerekir.

1.  [Google AI Studio](https://aistudio.google.com/) üzerinden bir API anahtarı edinin.
2.  Projeyi klonlayın veya indirin.
3.  `ChatBot/config.example.json` dosyasının adını `ChatBot/config.json` olarak değiştirin (veya kopyasını oluşturun).
4.  `config.json` dosyasını bir metin editörüyle açın ve `"YOUR_API_KEY_HERE"` yerine kendi API anahtarınızı yapıştırın.

```json
{
  "ApiKey": "BURAYA_API_ANAHTARINIZI_YAZIN"
}
```

**Önemli:** `config.json` dosyasını asla GitHub'a veya herkese açık bir yere yüklemeyin. `.gitignore` dosyası bu dosyanın yanlışlıkla yüklenmesini engeller.

### Çalıştırma

1.  `ChatBot.sln` dosyasını Visual Studio ile açın.
2.  Projeyi derleyin ve çalıştırın (F5).

## Katkıda Bulunma

Hataları bildirmek veya özellik isteğinde bulunmak için lütfen bir "Issue" açın.

## Lisans

MIT Lisansı ile lisanslanmıştır.
