# AI Agent ile Telegram, Ses ve Gmail Entegrasyonu

## 📄 Düzeltilmiş Anlatım Metni

Merhaba, Telegram üzerinden göndereceğiniz metin ve ses kayıtlarını anlayan, size cevap verebilen ve maillerinizi kontrol ederek mail göndermenizi sağlayan bir **AI Agent** kurgusu oluşturacağız.


## 🔹 Adım Adım Anlatım

1. **Trigger Ekleme**  
   Telegram’dan mesaj bilgisini almak için bir **Trigger** ekliyorum.  
   Başta Telegram olmak üzere kullanacağımız tüm uygulamalarda **API bilgilerine** ihtiyacımız var.  
   Bunun için üyelik oluşturup API bilgilerini kaydetmeliyiz.  
   *İsterseniz bu süreci başka bir videoda detaylı olarak gösterebilirim.*

2. **Switch Ekleme ve Test**  
   Metin ve ses göndereceğimiz için bir **Switch** ekliyoruz.  
   Ekledikten sonra ilk testimizi yapalım.

3. **Bot Oluşturma**  
   Telegram’da bot oluşturma adımlarını açıklama kısmına ekledim, oradan bakabilirsiniz.  
   Mesajı gönderip Trigger’ı tetiklediğimizde mesajın iletildiğini görüyoruz.

4. **Metin İşleme**  
   Gelen mesajın metin olup olmadığını anlaması için bir **Text** alanı ekliyorum.  
   Sonrasında, boş değilse devam etmesini sağlıyorum.

5. **Ses Dosyası İşleme**  
   Aynı işlemi ses dosyası için de yapıyoruz.  
   Burada seçimde bir hata yapıyorum ama ilerleyen adımlarda düzelteceğim.  
   Ses dosyası için önce indirmeniz gerekiyor.  
   Bunun için **Telegram – Get a file** seçiyoruz ve tekrar ses dosyası göndererek içeriği ekliyoruz.  
   Sonrasında bu dosyayı **Gemini yapay zekası** ile işliyoruz.

6. **AI Agent ve Hafıza Tanımı**  
   Bilgileri aldıktan sonra bunları **AI Agent**’a ekleyerek istediğimiz işlemleri yaptırıyoruz.  
   Ayrıca bilgileri hafızasında tutması için bir **Memory** tanımı ekliyoruz.  
   Buradaki sayılar rastgele belirlenmiştir.

7. **Sonucu Kullanıcıya Gönderme**  
   Sonucu kullanıcıya iletmek için **Telegram – Send a message** ekliyoruz.

8. **Gmail Entegrasyonu**  
   Birkaç testten sonra, Gmail üzerinden mail alma ve gönderme özelliğini de ekleyelim.  
   Testler sonunda sistemin sorunsuz çalıştığını ve istediğimiz bilgileri bize ilettiğini görüyoruz.

---

## 🎯 Sonuç
Bu çalışma ile Telegram üzerinden gelen metin ve sesleri işleyen, Gmail entegrasyonu ile mail gönderip alabilen bir AI Agent geliştirmiş olduk.

İzlediğiniz için teşekkürler.
