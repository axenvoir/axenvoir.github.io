# Expira Gizlilik Politikası | Expira Privacy Policy

**Son güncelleme / Last updated: 30 Ekim / October 30, 2026**

[English](#english) · [Türkçe](#türkçe)

## English

### Scope

This notice applies to the Expira Android application (`com.expira.app.tr`). It describes the current app's data practices. It does not govern Android, Google Play, Google Mobile Ads, Google UMP, your device-backup provider, or other services; those providers publish their own privacy terms.

### Information stored on your device

Expira stores the information you enter about products (such as product name, category, expiry date, quantity, and storage location), notes (title and content), and categories in the app's local database on your device. The app also stores limited preferences, including language, onboarding completion, and theme settings. Current support-point balances and owned cosmetic color palettes are stored in the same local database. When upgrading from an older version, the app can import a pre-existing point balance once from a legacy local preference file.
The app may also keep a simple local flag indicating that a reminder worker's last attempt ended in an error. This flag contains no product details or error text, is used to show a retry option in Settings, and is not included in the backup allowlist.
If a completed ad reward cannot immediately be saved, the app may temporarily keep an opaque event ID in local preferences so it can retry the same point credit after restart. The ID is removed after the Room save succeeds and is not included in the backup allowlist.
You may spend points on cosmetic color palettes. Five lifetime points also unlock a permanent Supporter badge. These points and items have no cash or transfer value.

The current app does not create an Expira user account or operate an Expira server that synchronizes your product or note contents. Search text is used in the active screen and is not kept as a search-history record.

### Advertising and privacy choices

Expira uses Google Mobile Ads Next-Gen SDK and User Messaging Platform (UMP) SDK. The app requests updated consent information through UMP when it launches. If an AdMob privacy message is required for your region or settings, UMP may present it. When UMP reports that a privacy-options entry is required, the app shows a “Privacy options” entry under Settings > Support to users eligible for ads. Expira requests a rewarded ad only when you start the ad flow; an ad request is made only when the app's purchase-entitlement and consent checks allow it. Watching an ad is optional and is not required to use products, notes, or reminders.

Google's published disclosure for the Mobile Ads Next-Gen SDK says that the SDK may automatically collect and share an IP address; app interactions such as launches, taps, and video views; diagnostic information such as app launch time, hang rate, and energy use; and device or account identifiers such as the Android advertising ID and App Set ID, and, where applicable, identifiers related to signed-in accounts on the device. Google states that these data are used for advertising, analytics, and fraud prevention and are encrypted in transit using TLS. SDK data practices may change with SDK versions and configuration; see Google's current disclosures linked below.

The ad type and related processing may depend on your consent choices, region, Android settings, and Google's/AdMob's configuration. You can manage Android advertising-ID settings through Android's settings. Expira's app code does not send your product or note contents to an Expira-operated server.

### Google Play purchases

The current app does not offer a new in-app purchase flow. It uses Google Play Billing to check for previously acquired subscription or one-time purchase entitlements so that existing ad-free rights can continue to be recognized and restored. Google Play processes the associated account and transaction information under Google's terms. Expira receives purchase information needed to determine the applicable entitlement and may acknowledge eligible purchases to Google Play; it does not send purchase information to an Expira-operated backend.

### Notifications, backups, and exports

If you enable reminders and grant notification permission, Expira schedules local notifications on your device using your saved product and expiry-date information. The app does not operate a remote push-notification server. A reminder can contain product names and expiry details in its private notification content. It is marked private and supplies generic public text for Android lock screens that hide private content; the actual preview depends on your device's notification and lock-screen settings.

Android's backup and device-transfer features may include the app's main database, which contains product/category/note data, the local reward-point balance, and unlocked cosmetic palettes, as well as selected preferences (language, onboarding, and theme). The legacy point-balance preference is also allowlisted temporarily for one-time migration from older versions; pending reward-retry IDs, ad-consent preferences, and reminder-health flags are excluded. On Android 12 and later, Expira's cloud-backup rules opt out if the OS reports that client-side encryption is unavailable. The legacy full-backup rules on Android 11 and earlier do not provide the same encryption-capability check. Android and your Google/device account control whether a backup or transfer occurs, and no backup or transfer is guaranteed.

If you export data as a CSV file, Android lets you choose where to save it. Expira does not upload that file to an Expira server. The selected storage, cloud-drive, or sharing provider may process the file under its own terms. Copies you export or back up may remain after you delete the original in Expira, so remove those copies separately if you no longer need them.

### Crash recovery

For local crash recovery, Expira may temporarily save the exception type and a limited number of stack-frame details in the app's private, non-backup storage. The app reads and removes this recovery marker on the next startup. Expira does not send this marker to an Expira crash-reporting server.

### Retention and deletion

Your product, category, and note records remain in the app until you delete them, clear the app's storage, or uninstall the app. Android backup copies and CSV files are managed separately by Android or the destination you selected. Expira does not provide an online account from which product or note records can be retrieved or remotely deleted.

### Children

Expira is not designed for children. Google Mobile Ads and Google Play may process data under their own policies and the publisher's configured audience, advertising, and consent settings.

### Contact and policy changes

For privacy questions, contact the publisher at [axenvoir@yahoo.com](mailto:axenvoir@yahoo.com). If you email us, the message and sender address you include will be processed to respond to your request; your email provider's terms also apply.

This policy may be updated when the app or its data practices change. The latest version is published at [axenvoir.github.io](https://axenvoir.github.io/).

### Third-party privacy information

- [Google Mobile Ads Next-Gen SDK data disclosure](https://developers.google.com/admob/android/next-gen/privacy/play-data-disclosure)
- [Google UMP SDK privacy and consent information](https://developers.google.com/admob/android/next-gen/privacy)
- [Google Privacy Policy](https://policies.google.com/privacy)
- [Google Play Data safety guidance for developers](https://support.google.com/googleplay/android-developer/answer/10787469?hl=en)

## Türkçe

### Kapsam

Bu bildirim, Expira Android uygulaması (`com.expira.app.tr`) için geçerlidir ve mevcut sürümün veri işleme uygulamalarını açıklar. Android, Google Play, Google Mobile Ads, Google UMP, cihaz yedekleme sağlayıcınız veya diğer hizmetler bu politikanın kapsamında değildir; bu sağlayıcıların kendi gizlilik koşulları bulunur.

### Cihazınızda saklanan bilgiler

Expira; ürünler için girdiğiniz ürün adı, kategori, son kullanma tarihi, miktar ve saklama yeri gibi bilgileri, notların başlık ve içeriğini ve kategorileri cihazınızdaki yerel uygulama veritabanında saklar. Uygulama ayrıca dil, ilk kurulumun tamamlanma durumu ve tema ayarları gibi sınırlı tercihleri tutar. Güncel destek puanı bakiyesi ve açılmış kozmetik renk paletleri aynı yerel veritabanındadır. Eski bir sürümden yükseltme sırasında uygulama, önceki yerel tercihler dosyasında bulunan puan bakiyesini bir kez içe aktarabilir.
Uygulama ayrıca hatırlatıcı çalışanının son denemesinin hata ile bittiğini belirten basit bir yerel işaret tutabilir. Bu işaret ürün ayrıntılarını veya hata metnini içermez; yalnızca Ayarlar'da yeniden deneme seçeneği göstermek için kullanılır ve yedekleme izin listesine dahil değildir.
Tamamlanan bir reklam ödülü hemen kaydedilemezse uygulama, yeniden başlatma sonrasında aynı puan işlemini tekrar deneyebilmek için yerel tercihlerde geçici, kimlik bilgisi içermeyen bir olay kodu tutabilir. Room kaydı başarılı olduğunda bu kod silinir ve yedekleme izin listesine dahil değildir.
Puanları kozmetik renk paletlerinin kilidini açmak için harcayabilirsiniz. Ömür boyu kazanılan 5 puan ayrıca kalıcı bir Destekçi rozeti açar. Puanların ve öğelerin nakit veya devredilebilir değeri yoktur.

Mevcut uygulama bir Expira kullanıcı hesabı oluşturmaz ve ürün veya not içeriklerinizi eşitleyen Expira sunucusu işletmez. Arama metni açık olan ekranda kullanılır; arama geçmişi olarak saklanmaz.

### Reklamlar ve gizlilik tercihleri

Expira, Google Mobile Ads Next-Gen SDK ve User Messaging Platform (UMP) SDK’larını kullanır. Uygulama her açıldığında UMP üzerinden güncel kullanıcı rıza bilgilerini sorgular. AdMob’un bölgeniz veya ayarlarınız için bir gizlilik mesajı gerekiyorsa UMP bu mesajı gösterebilir. UMP uygulama içinden gizlilik seçeneklerine erişim sunulmasını gerekli görürse reklam gösterimine uygun kullanıcılar Ayarlar > Destek bölümündeki “Gizlilik tercihleri” seçeneğini kullanabilir. Expira, ödüllü reklam isteğini yalnızca siz reklam akışını başlattığınızda gönderir; bu istek ancak satın alma hakkı ve rıza kontrolleri uygunsa yapılır. Reklam izlemek isteğe bağlıdır; ürünleri, notları veya hatırlatıcıları kullanmak için zorunlu değildir.

Google’ın Mobile Ads Next-Gen SDK için yayımladığı açıklamaya göre SDK; IP adresini, uygulama etkileşimlerini (uygulamanın açılması, dokunmalar ve video görüntüleme gibi), tanılama bilgilerini (uygulamanın açılma süresi, takılma oranı ve enerji kullanımı gibi) ve Android reklam kimliği ile App Set ID gibi cihaz/hesap tanımlayıcılarını; varsa cihazda oturum açılmış hesaplarla ilişkili diğer tanımlayıcıları otomatik olarak toplayıp paylaşabilir. Google, bu verilerin reklam sunumu, analiz ve sahtekârlığı önleme amaçlarıyla kullanıldığını ve aktarım sırasında TLS ile şifrelendiğini belirtir. SDK’nin veri işleme uygulamaları sürüm ve yapılandırmaya göre değişebilir; güncel açıklamalar aşağıdaki Google bağlantılarında yer alır.

Gösterilen reklamın türü ve buna bağlı veri işleme, gizlilik tercihlerinize, bölgenize, Android ayarlarınıza ve Google/AdMob yapılandırmasına bağlı olabilir. Android reklam kimliğiyle ilgili seçenekleri cihaz ayarlarından yönetebilirsiniz. Expira uygulama kodu ürün veya not içeriklerinizi Expira tarafından işletilen bir sunucuya göndermez.

### Google Play satın alımları

Mevcut uygulamada yeni uygulama içi satın alma akışı sunulmaz. Daha önce edinilmiş abonelik veya tek seferlik satın alım haklarının tanınması ve geri yüklenebilmesi için Google Play Billing üzerinden mevcut haklar kontrol edilir. İlgili hesap ve işlem bilgileri Google’ın koşulları uyarınca Google Play tarafından işlenir. Expira hak durumunu belirlemek için gerekli satın alma bilgilerini alır ve gerektiğinde eski satın alımların işlendiğini Google Play’e bildirir; satın alma bilgilerini Expira tarafından işletilen bir sunucuya göndermez.

### Bildirimler, yedekleme ve dışa aktarma

Hatırlatıcıları etkinleştirip bildirim izni verirseniz Expira, kayıtlı ürün ve son kullanma tarihi bilgilerinizi kullanarak cihazınızda yerel bildirimler planlar. Uygulama uzaktan bildirim gönderen bir sunucu işletmez. Bildirimin özel içeriğinde ürün adları ve son kullanma bilgileri bulunabilir. Bildirim özel olarak işaretlenir ve Android özel içeriği kilit ekranında gizlediğinde genel bir Expira metni sunar; gerçek önizleme cihazınızın bildirim ve kilit ekranı ayarlarına bağlıdır.

Android yedekleme veya cihazlar arası aktarım özellikleri etkin ve destekleniyorsa ürün/kategori/not verileri, yerel ödül puanı bakiyesi ve açılmış kozmetik paletleri içeren ana veritabanını ve seçili tercihleri (dil, ilk kurulum durumu ve tema) yedeklemeye veya aktarmaya dahil edebilir. Eski puan bakiyesini tek seferlik içe aktarmak için önceki sürümün yerel puan tercih dosyası da geçici olarak izin listesindedir; bekleyen ödül tekrar-deneme kimlikleri, reklam rızası tercihleri ve hatırlatıcı sağlık işaretleri yedeklenmez. Android 12 ve üzeri bulut yedeklemesi, işletim sistemi istemci tarafı şifrelemenin kullanılamadığını bildirirse devre dışı bırakılır. Android 11 ve altındaki eski tam yedekleme kuralları aynı şifreleme-yeteneği kontrolünü sağlamaz. Yedekleme veya aktarım yapılıp yapılmayacağını Android ve Google/cihaz hesabı ayarlarınız belirler; yedekleme veya aktarım garanti edilmez.

Verileri CSV olarak dışa aktarırsanız dosyanın kaydedileceği yeri Android üzerinden siz seçersiniz. Expira bu dosyayı kendi sunucusuna yüklemez. Seçtiğiniz depolama, bulut sürücüsü veya paylaşım sağlayıcısı dosyayı kendi koşullarına göre işleyebilir. Dışa aktardığınız veya yedeklenen kopyalar Expira’daki asıl veriyi sildikten sonra da kalabilir; artık istemiyorsanız bu kopyaları ayrıca silin.

### Çökme kurtarma

Yerel çökme kurtarma için Expira, hata türünü ve sınırlı sayıda çağrı yığını ayrıntısını uygulamanın özel, yedeklenmeyen depolama alanına geçici olarak kaydedebilir. Uygulama bir sonraki açılışta bu kurtarma işaretini okur ve siler. Expira bu işareti Expira tarafından işletilen bir çökme raporlama sunucusuna göndermez.

### Saklama ve silme

Ürün, kategori ve not kayıtlarınız; siz onları uygulama içinden silene, uygulama depolamasını temizleyene veya uygulamayı kaldırana kadar cihazda kalır. Android yedekleri ve CSV dosyaları Android ya da seçtiğiniz hedef tarafından ayrıca yönetilir. Expira, ürün veya not kayıtlarını uzaktan görüntüleyip silebileceğiniz çevrimiçi bir kullanıcı hesabı sunmaz.

### Çocuklar

Expira çocuklara yönelik tasarlanmamıştır. Google Mobile Ads ve Google Play verileri kendi politikalarına ve yayıncının yapılandırdığı hedef kitle, reklam ve izin ayarlarına göre işleyebilir.

### İletişim ve politika değişiklikleri

Gizlilikle ilgili sorularınız için yayıncıya [axenvoir@yahoo.com](mailto:axenvoir@yahoo.com) adresinden ulaşabilirsiniz. Bize e-posta gönderirseniz talebinize yanıt vermek için e-posta içeriğiniz ve gönderici adresiniz işlenir; e-posta sağlayıcınızın koşulları da geçerlidir.

Uygulama veya veri işleme uygulamaları değiştiğinde bu politika güncellenebilir. En güncel sürüm [axenvoir.github.io](https://axenvoir.github.io/) adresinde yayımlanır.

### Üçüncü taraf gizlilik bilgileri

- [Google Mobile Ads Next-Gen SDK veri açıklaması](https://developers.google.com/admob/android/next-gen/privacy/play-data-disclosure)
- [Google UMP SDK gizlilik ve izin bilgileri](https://developers.google.com/admob/android/next-gen/privacy)
- [Google Gizlilik Politikası](https://policies.google.com/privacy)
- [Google Play geliştirici Data Safety rehberi](https://support.google.com/googleplay/android-developer/answer/10787469?hl=en)
