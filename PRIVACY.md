# Lux — Privacy Policy / Политика конфиденциальности

Last updated / Обновлено: 25 September 2026 / 25 сентября 2026

## English

This policy covers **Lux — Light & Color Tool** for iPhone and iPad, developed by Artem Leonov. It includes the optional Studio features introduced in Lux 3.0.

### Data in the app

Lux works on your device without an account. The app does not send personal data, camera images, videos, audio, measurements, or saved colors to the developer. It contains no advertising, analytics, tracking, or third-party analytics SDKs. Most features work offline. Optional model downloads and nearby light control use the network as described below.

Lux saves your favorite colors, selected settings, saved lighting scenes, language preference, and whether introductory hints have been shown in local app storage. The developer has no remote access to this data. It remains on your device until you remove it, including by deleting the app through iOS. Device backups are controlled by your system settings.

### Camera, selected photos, and sharing

Camera access is optional and requested for the light meter, eyedropper, selfie mirror, or taking a photo for a Studio tool. The live camera feed is processed on the device. The selfie mirror takes a photo only when you press the shutter or start its countdown, and records a video only when you press Record; a recording stops after at most three minutes. Microphone access is requested only when you switch the selfie mirror to Video and is used only for the sound of that video; if you decline, the video is recorded without sound. Lux does not upload camera images, videos or audio to the developer. Other lighting modes work without camera or microphone permission. You can revoke these permissions in iOS Settings.

The photo palette and lighting coach receive only the image you select using the system photo picker or take for that tool. Lux processes the image locally to extract colors or suggest a lighting plan. For the lighting plan, on-device face detection (Apple's Vision framework) finds the face and Lux measures how brightly each side of it is lit, to estimate where the light comes from and to place the subject marker. This measurement exists only while the tool is open and is not stored or sent anywhere. Lux does not identify people, does not create face templates, and does not build a face identity database. If you select an item stored in iCloud Photos, the system may download it according to your Apple settings.

Selected and captured images are held for the current tool session. A recorded video is kept as a temporary file inside the app until you retake it or leave the selfie mirror; leftover temporary clips are deleted the next time the selfie camera starts. A temporary copy used for local model analysis is removed when that analysis finishes or is cancelled. Saving a lighting scene stores its lighting settings, not the source photo. A selfie photo or video is added to your photo library only when you choose Save photo or Save video and grant the system's add-only permission. Saved photos and videos and any iCloud Photos synchronization are then managed by your system settings.

You can also choose to share a photo, video or lighting-plan image using the system share sheet. The destination app or service handles what you share under its own terms and privacy practices.

### Optional local model download

The lighting coach reads the light from your photo on the device without any download. On supported devices it also offers an optional Qwen model download of approximately 1.75 GB, which refines the plan (for example, whether the light comes from a window or a lamp). Downloading requires an internet connection and is started by you. Model files are retrieved from Hugging Face and its delivery providers over HTTPS. Those providers receive the usual download connection information, such as your IP address and requested file URLs. Lux does not send your selected photos, lighting plans, or analysis prompts to them. See [Hugging Face's Privacy Policy](https://huggingface.co/privacy).

After the download, photo analysis runs on the device. The model files are stored locally, excluded from device backups, and can be deleted in the lighting coach's On-device assistant settings. The coach's photo reading and editable plans remain available without downloading a model.

### Nearby light control

When you choose the controller or light role, Lux uses Apple's Multipeer Connectivity framework to discover nearby devices. Device names are visible to nearby Lux controllers during discovery, before pairing. A six-digit code shown on the light device is required to connect. After pairing, the controller can send selected lighting settings and start/stop commands over an encrypted connection. Lux does not send photos, camera feeds, or photo-analysis data through this connection.

Nearby control requires the relevant system network permissions. The connection is not routed through a developer-operated server. Choose Disconnect, leave Studio, or put the app in the background to end nearby control.

### Clipboard

When you tap **Copy HEX**, Lux places the selected color code on the system clipboard. The clipboard is managed by iOS and can be available to other apps or devices according to your system settings. Lux does not monitor the clipboard, read it automatically, or upload its contents.

### Support and this website

If you email support, the developer receives your email address and the information you choose to include. This correspondence is used to respond to and resolve your request, and is retained only as needed for that purpose or applicable legal obligations. Email is handled by the sending and receiving email providers. You can contact the developer to request deletion of support correspondence.

This public documentation is hosted by GitHub. Visiting it is separate from using the app and is subject to [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

### Contact and updates

For privacy questions or requests, contact **Artem Leonov** at [artemleonov@yahoo.com](mailto:artemleonov@yahoo.com).

Changes to this policy will be published on this page with an updated date.

## Русский

Эта политика относится к приложению **Lux — Light & Color Tool** для iPhone и iPad. Разработчик — Артём Леонов. Она также описывает дополнительные функции «Студии», появившиеся в Lux 3.0.

### Данные в приложении

Lux работает на устройстве без учётной записи. Приложение не отправляет разработчику персональные данные, изображения с камеры, видео, звук, измерения или сохранённые цвета. В нём нет рекламы, аналитики, отслеживания и сторонних SDK аналитики. Большинство функций работает без интернета. Необязательная загрузка модели и управление соседними источниками света используют сеть, как описано ниже.

Lux сохраняет избранные цвета, выбранные настройки, сохранённые сцены освещения, язык и информацию о показе начальных подсказок в локальном хранилище приложения. Разработчик не имеет удалённого доступа к этим данным. Они остаются на устройстве до удаления, в том числе при удалении приложения средствами iOS. Резервное копирование устройства определяется системными настройками.

### Камера, выбранные фотографии и отправка

Доступ к камере необязателен и запрашивается для люксметра, пипетки, селфи-зеркала или съёмки фотографии для инструмента «Студии». Изображение с камеры обрабатывается на устройстве. Селфи-зеркало делает фотографию только после нажатия кнопки съёмки или запуска отсчёта и записывает видео только после нажатия кнопки записи; запись длится не более трёх минут. Доступ к микрофону запрашивается только при переключении селфи-зеркала в режим «Видео» и используется только для звука этого видео; если его не дать, видео записывается без звука. Lux не отправляет разработчику изображения с камеры, видео или звук. Остальные режимы подсветки работают без разрешений камеры и микрофона. Отозвать разрешения можно в настройках iOS.

Палитра по фото и помощник по свету получают только изображение, которое вы выбрали в системном окне выбора фотографий или сняли для этого инструмента. Lux обрабатывает его на устройстве, чтобы выделить цвета или предложить схему освещения. Для схемы освещения локальное обнаружение лица (фреймворк Vision от Apple) находит лицо, а Lux измеряет, насколько ярко освещена каждая его сторона, чтобы оценить, откуда падает свет, и поставить маркер человека. Этот замер существует только пока открыт инструмент и никуда не сохраняется и не передаётся. Lux не устанавливает личность, не создаёт шаблоны лиц и не создаёт базу для идентификации лиц. При выборе снимка из «Фото iCloud» система может загрузить его согласно настройкам Apple.

Выбранные и сделанные фотографии используются в текущем сеансе инструмента. Записанное видео хранится во временном файле внутри приложения, пока вы не переснимете его или не выйдете из селфи-зеркала; оставшиеся временные клипы удаляются при следующем запуске камеры селфи-зеркала. Временная копия для анализа локальной моделью удаляется после завершения или отмены анализа. Сохранение сцены сохраняет настройки света, а не исходную фотографию. Фото или видео из селфи-зеркала добавляется в медиатеку только после выбора «Сохранить фото» или «Сохранить видео» и предоставления системного разрешения на добавление. Сохранённые фото и видео и их синхронизация через iCloud далее зависят от системных настроек.

Вы также можете отправить фотографию, видео или изображение схемы через системное меню отправки. Выбранное приложение или сервис обрабатывает их по собственным условиям и правилам конфиденциальности.

### Необязательная загрузка локальной модели

Помощник по свету определяет свет по фотографии на устройстве без каких-либо загрузок. На поддерживаемых устройствах он также предлагает необязательную загрузку модели Qwen размером около 1,75 ГБ, которая уточняет схему (например, окно это или лампа). Для загрузки нужен интернет; её запускаете вы. Файлы модели загружаются с Hugging Face и через его поставщиков доставки по HTTPS. Эти поставщики получают обычные сведения о соединении, например IP-адрес и адреса запрашиваемых файлов. Lux не отправляет им выбранные фотографии, схемы освещения или запросы для анализа. См. [политику конфиденциальности Hugging Face](https://huggingface.co/privacy).

После загрузки анализ фотографии выполняется на устройстве. Файлы модели хранятся локально, исключены из резервных копий устройства и могут быть удалены в настройках «Локальный помощник» помощника по свету. Определение света по фото и редактируемые схемы доступны без загрузки модели.

### Управление соседними источниками света

После выбора роли пульта или источника света Lux использует Multipeer Connectivity от Apple для поиска соседних устройств. Имена устройств видны находящимся рядом пультам Lux во время поиска, ещё до сопряжения. Для подключения нужен шестизначный код, показанный на устройстве-источнике. После сопряжения пульт может отправлять выбранные настройки света и команды запуска и остановки по зашифрованному соединению. Через него Lux не передаёт фотографии, изображение с камеры или данные анализа снимка.

Для управления нужны соответствующие системные разрешения сети. Соединение не проходит через сервер разработчика. Нажмите «Отключиться», выйдите из «Студии» или переведите приложение в фон, чтобы завершить управление.

### Буфер обмена

Когда вы нажимаете **Копировать HEX**, Lux помещает выбранный код цвета в системный буфер обмена. Буфером управляет iOS; доступ к нему других приложений и устройств зависит от системных настроек. Lux не отслеживает буфер обмена, не читает его автоматически и не загружает его содержимое.

### Поддержка и этот сайт

Если вы пишете в поддержку, разработчик получает адрес вашей электронной почты и сведения, которые вы решили включить в письмо. Переписка используется для ответа и решения вашего вопроса и хранится только пока нужна для этой цели или исполнения применимых требований закона. Письма обрабатываются почтовыми сервисами отправителя и получателя. Можно обратиться к разработчику с просьбой удалить переписку с поддержкой.

Эта публичная документация размещена на GitHub. Её посещение происходит отдельно от использования приложения и регулируется [политикой конфиденциальности GitHub](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

### Контакты и обновления

По вопросам конфиденциальности обращайтесь к **Артёму Леонову**: [artemleonov@yahoo.com](mailto:artemleonov@yahoo.com).

Изменения политики будут опубликованы на этой странице с новой датой обновления.

