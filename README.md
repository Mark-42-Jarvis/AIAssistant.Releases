# AI Assistant

[![Türkçe](https://img.shields.io/badge/Dil-Türkçe-red)](README.md)

AI Assistant, Windows üzerinde çalışan ve **kişisel AI asistanı** olmak için tasarlanan bir masaüstü uygulamasıdır.

Amacım sadece soru sorup cevap aldığınız bir chat uygulaması yapmak değil. AI Assistant'ın zamanla bilgisayarınızda sizinle birlikte çalışan, ihtiyaç duyduğunuz işlemleri yapabilen ve günlük kullanımda gerçekten bir kişisel asistana dönüşen bir uygulama olması.

> 🚧 **AI Assistant hala aktif olarak geliştiriliyor.** Özellikler değişebilir, yeni özellikler eklenebilir ve özellikle Alpha / Beta sürümlerde hatalarla karşılaşabilirsiniz.

---

# 👇 AI ASSISTANT'I İNDİR

### Windows Setup üzerinden kurmak için:

## **[⬇️ AI ASSISTANT SETUP'I BURADAN İNDİR](https://github.com/Mark-42-Jarvis/AIAssistant.Releases/releases/download/Download/AIAssistant.Setup.rar)**

Setup'ı indirdikten sonra arşivden çıkartıp kurulumu başlatabilirsiniz. Setup gerekli AI Assistant dosyalarını indirip kurulumu tamamlar.

---

## Release Channels

| Channel | Ne anlama geliyor? |
| --- | --- |
| **Stable** | Normal kullanım için önerilen sürüm |
| **Beta** | Yeni özelliklerin daha geniş kapsamlı test edildiği sürüm |
| **Alpha** | En yeni özelliklerin bulunduğu erken geliştirme sürümü |

Yeni sürümleri, Alpha / Beta test build'lerini ve Stable sürümleri buradan takip edebilirsiniz:

**👉 [Tüm AI Assistant Releases](https://github.com/Mark-42-Jarvis/AIAssistant.Releases/releases)**

## Kurulum

AI Assistant kendi Windows Installer'ı ile kurulabilir. Gerekli uygulama dosyaları Installer tarafından hazırlanır.

Ayrıca .NET, Node.js, Angular CLI veya benzeri development araçlarını kurmanız gerekmez.

## Verileriniz Nerede Tutuluyor?

AI Assistant'ın size ait verileri uygulamanın kurulu olduğu bilgisayardaki **Data** klasöründe tutulur.

Temel kurulum yapısı şu şekildedir:

```text
AI Assistant/
├── App/       # Uygulama dosyaları
├── Data/      # Size ait kalıcı veriler
└── Updater/   # Update sistemi
```

`App` klasörü yeni bir release ile değişebilir. `Data` klasörü ise uygulama update edildiğinde korunur. Böylece uygulamayı güncellediğinizde kişisel verileriniz silinmez.

AI Assistant local verilerini SQLite üzerinde saklar. Bunun için ayrıca SQL Server veya başka bir database server kurmanız gerekmez.

## Memory

AI Assistant'ın önemli özelliklerinden biri **Memory** yapısıdır.

Amaç, her konuşmaya tamamen sıfırdan başlayan bir AI yerine; sizin özellikle kalıcı olmasını istediğiniz bilgileri, tercihleri ve kullandığınız isimlerin ne anlama geldiğini hatırlayabilen kişisel bir asistan oluşturmaktır.

Örneğin bir proje için kullandığınız özel bir isim, tercihleriniz veya daha sonra tekrar kullanılmasını istediğiniz bir bilgi Memory olarak kaydedilebilir. Bu bilgiler sonraki oturumlarda tekrar kullanılabilir.

Memory kayıtları da AI Assistant'ın local Data yapısında tutulur. Yani uygulamanın kendi kalıcı verilerinin bir parçasıdır ve normal bir update sırasında silinmez.

Memory sistemi de AI Assistant'ın geri kalanı gibi aktif olarak geliştirilmeye devam ediyor.

## Update

AI Assistant kendi update sistemine sahiptir. Yeni bir sürüm yayınlandığında uygulama bunu kontrol edebilir ve size yeni sürüm olduğunu gösterebilir.

Update işlemini uygulama içerisinden başlatabileceğiniz gibi AI Assistant'a doğrudan:

> **Kendini güncelle**

demeniz de yeterlidir.

AI Assistant yeni sürümü indirir, uygulamayı kapatır, update işlemini tamamlar ve tekrar açar.

## Release Channel Seçimi

AI Assistant üç farklı release channel kullanır: **Stable**, **Beta** ve **Alpha**.

Hangi channel'ı takip etmek istediğinizi uygulamanın Settings bölümünden seçebilirsiniz. Stable varsayılan seçenektir.

## Platform

- Windows 10 / 11
- x64
- Self-contained .NET application

## Repository Hakkında

Bu repository, AI Assistant'ın public release dosyalarını yayınlamak ve uygulamanın update sistemini çalıştırmak için kullanılıyor.

Source code burada paylaşılmıyor. Bu repository içerisinde ağırlıklı olarak GitHub Releases ve uygulamanın dağıtımıyla ilgili dosyalar bulunuyor.

## License

MIT License ile yayınlanmaktadır. Detaylar için [`LICENSE`](LICENSE) dosyasına bakabilirsiniz.

## Website

https://tanersaydam.net
