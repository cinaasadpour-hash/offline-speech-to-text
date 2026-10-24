# Offline Speech to Text | گفتار به متن آفلاین

![Icon](icon.png)

[Download / دریافت برنامه](https://github.com/cinaasadpour-hash/offline-speech-to-text/releases/latest)

## فارسی

تبدیل گفتار ضبط‌شده و فایل صوتی به متن روی گوشی با مدل Whisper.

اندروید ۱۰ به بالا و پردازنده ARM با معماری ۶۴بیتی لازم است. از بخش مدل‌ها یک مدل دریافت کنید، زبان گفتار را انتخاب و سپس صدا ضبط یا فایل وارد کنید. هر فایل یا ضبط حداکثر پنج دقیقه است. متن را پیش از استفاده بازبینی کنید.

### تبلیغات

بنر استاندارد در تنظیمات و اطلاعات دستگاه؛ بینابینی محدود پس از ذخیرهٔ موفق متن و خروج از بخش تبدیل. ضبط و تبدیل صدا بدون نمایش تبلیغ انجام می‌شوند.

نمایش تبلیغ به اینترنت و موجودی شبکهٔ تبلیغات بستگی دارد. امکانات اصلی به دریافت تبلیغ وابسته نیستند. تبلیغ بینابینی هنگام شروع برنامه نمایش داده نمی‌شود و تعداد نمایش آن محدود است.

## English

Transcribe recordings and audio files locally on your phone with Whisper.

Requires Android 10+ and a 64-bit ARM processor. Download a model from Models, choose the speech language, then record or import audio. Each input is limited to five minutes. Review the generated transcript before use.

### Advertising

Standard banner in Settings and Device information; a capped interstitial after a successful text export when leaving Transcribe. No ads during recording or transcription.

Advertising requires an internet connection and available inventory. Core features do not depend on an ad being available. Interstitials are not shown on launch and are frequency-capped.

Package: `com.sinatools.offlinespeechtotext` · Version: **1.0.1** · Minimum Android API: **29** · Target SDK: **36**.

See [Privacy / حریم خصوصی](PRIVACY.md). Release APKs are signed with the publisher’s release certificate; private signing keys are not included in this repository.

The speech engine uses [whisper.cpp](https://github.com/ggml-org/whisper.cpp). Models are downloaded separately; recognition speed and accuracy depend on the model, device, language and recording quality.
