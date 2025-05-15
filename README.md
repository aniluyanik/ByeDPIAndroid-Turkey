# ByeDPIAndroid Kurulum Kılavuzu (Türkiye Ayarları)

## 

1. **Uygulamayı İndirin:**

   - https://github.com/dovecoteescapee/ByeDPIAndroid/releases

2. **Uygulamayı Açın:**

   - Uygulamayı kurun ve açın. Sağ üst köşedeki dişli çark simgesine (⚙️) dokunarak "Settings" menüsüne gidin.

3. **General Ayarları Yapın:**

   - **Mode:** "VPN" seçeneğini aktif edin.
   - **DNS:** "1.1.1.1" yazın.
   - **IPv6:** Kapalı bırakın.

4. **Byedpi Ayarları:**

   - **Use command line settings:** Kapalı bırakın.
   - **UI Editor** seçeneğine girin

5. **Proxy Ayarları:**

   - **Listen address:** "127.0.0.1" yazın.
   - **Port:** "1080" girin.
   - **Maximum number of connections:** "512" yazın.
   - **Buffer size:** "16384" girin.

6. **Desync Ayarları:**

   **Blacklist** Ayarları:

   - "Hosts" sekmesini açın ve "Blacklist" seçin "Hosts blacklist" kısmına şu alan adlarını ekleyin:

   ```
   discord.com
   discord.gg
   discordapp.com
   discordapp.io
   discordapp.net
   discord.media
   discordcdn.com
   discordstatus.com
   discord-attachments-uploads-prd.storage.googleapis.com
///
   - **Desync HTTP:** Açık yapın.
   - **Desync HTTPS:** Açık yapın.
   - **Desync UDP:** Açık yapın. (Ses kanalları çalışmıyor ise açık yapın.)
   - **UDP fake count:** Değeri 10 yazın, ses kanalları çalışmaz ise size uygun değeri bulun. ("Desync UDP" açmadıysanız bu adımı atlayın.)
   - **Host mixed case:** Açık yapın.
   - Diğer ayarları (örneğin "Default TTL", "Split position" gibi) varsayılan değerlerde bırakabilirsiniz.

7. **Uygulamayı Başlatın:**

   - Ayarları yaptıktan sonra ana ekrana dönün ve "Connect" butonuna dokunarak VPN bağlantısını aktif edin. İnternet bağlantınızı kontrol edin.

### Bilgilendirme

- Bu ayarlar TürkTelekom ile test edilmiştir eğer sizin sağlayıcınızda çalışmaz ise birkaç ayarları değiştirmeyi deneyin.
- İsterseniz ByeDPI kısayolunu Hızlı Ayarlar menüsüne kısayol olarak ekleyebilirsiniz.
- Bu proje benim tarafımdan geliştirilmemiştir. Sadece yukarıdaki bilgiler eğitim amaçlıdır ve herhangi bir sorumluluk kabul etmiyorum.
