# Политика конфиденциальности ХаронТВ (HaronTV)

**Дата последнего обновления: 16 ноября 2026**

ХаронТВ (пакет `com.vamp.haron.tv`) — файловый менеджер для Android TV и приставок. Автор — Виктор Уткин.

## 1. Какие данные собираются

Никакие. ХаронТВ не собирает, не хранит у себя и не передаёт автору личные данные.
- **Файлы и настройки** хранятся только на вашем устройстве.
- **Пароли и ключи** к сетевым папкам и облакам хранятся на устройстве в зашифрованном виде (Android Keystore). Автор и третьи лица к ним доступа не имеют.

## 2. Аналитика и отчёты об ошибках

ХаронТВ не использует сервисы аналитики, телеметрии и отправки отчётов об ошибках. Журнал работы приложения хранится на устройстве; он уходит куда-либо, только если вы сами им поделитесь.

## 3. Сеть

- **Сетевые папки (SMB, FTP, SFTP, WebDAV) и облака (Google Drive, Dropbox, Яндекс Диск)** — приложение подключается напрямую к серверам, которые вы указали. Вход в облака — через официальный OAuth; данные читаются и пишутся только по вашей команде.
- **Торренты** — при скачивании раздачи ваш IP-адрес видят другие участники раздачи; так устроен протокол BitTorrent.
- **Передача файлов и серверы** (FTP/SMB-сервер, раздача по ссылке, передача между устройствами) — работают в вашей локальной сети и только пока вы их включили.
- **Трансляция (Google Cast, повтор экрана)** — запускается только вами.

## 4. Разрешения

- **Доступ ко всем файлам** — чтобы работать с файлами на устройстве и флешках.
- **Сеть, Wi-Fi** — сетевые папки, облака, торренты, передача файлов.
- **Местоположение, Bluetooth, устройства поблизости** — Android требует их для поиска соседних устройств при передаче файлов. Координаты не определяются и не сохраняются.
- **Микрофон** — голосовые команды, только когда вы их запускаете. Речь распознаёт системная служба распознавания вашего устройства.
- **Камера** — на устройствах с камерой; на приставках без камеры не используется. QR-коды распознаются прямо с картинки, на устройстве.
- **Установка и удаление приложений, список приложений** — менеджер приложений: установка APK, извлечение APK, удаление по вашей команде.
- **Биометрия** — блокировка приложения и защищённой папки, если вы их включили.
- **Уведомления, работа в фоне, автозапуск** — для операций с файлами, серверов и плеера, которые продолжают работать в фоне.

Ни одно разрешение не используется для сбора данных.

## 5. Сторонние библиотеки

ХаронТВ использует библиотеки с открытым исходным кодом (например, VLC для видео, JSch для SFTP). Распознавание текста и QR-кодов работает на устройстве. Автор не передаёт ваши данные разработчикам библиотек.

## 6. Дети

Приложение не собирает данные ни о ком, в том числе о детях.

## 7. Изменения

При изменении политики меняется дата в её начале.

## 8. Связь

vampilenna@gmail.com · https://github.com/Dolgoibimus/HaronTV

---

# Privacy Policy for HaronTV

**Last updated: November 16, 2026**

HaronTV (package `com.vamp.haron.tv`) is a file manager for Android TV and set-top boxes. Author: Viktor Utkin.

## 1. Data collection

None. HaronTV does not collect, keep or send any personal data to the author.
- **Files and settings** stay on your device.
- **Passwords and keys** for network shares and cloud accounts are stored on the device, encrypted with Android Keystore. Neither the author nor third parties can access them.

## 2. Analytics and crash reports

HaronTV uses no analytics, telemetry or crash-reporting services. The app log stays on the device and leaves it only if you share it yourself.

## 3. Network

- **Network shares (SMB, FTP, SFTP, WebDAV) and cloud storage (Google Drive, Dropbox, Yandex Disk)** — the app connects directly to the servers you configure. Cloud sign-in uses official OAuth; data is accessed only to perform your actions.
- **Torrents** — while downloading, your IP address is visible to other peers; this is how BitTorrent works.
- **File transfer and servers** (FTP/SMB server, share by link, device-to-device transfer) — work in your local network and only while you keep them on.
- **Casting (Google Cast, screen mirroring)** — started only by you.

## 4. Permissions

- **All files access** — to manage files on the device and USB drives.
- **Network, Wi-Fi** — network shares, cloud, torrents, file transfer.
- **Location, Bluetooth, nearby devices** — required by Android to discover nearby devices for file transfer. Your location is not determined or stored.
- **Microphone** — voice commands, only when you start them. Speech is recognized by your device's system speech service.
- **Camera** — on devices that have one; not used on boxes without a camera. QR codes are recognized from images on the device.
- **Install/delete packages, list of apps** — app manager: installing APKs, extracting APKs, uninstalling on your command.
- **Biometrics** — app lock and secure folder, if you enable them.
- **Notifications, background work, start on boot** — for file operations, servers and the player that keep running in the background.

No permission is used to collect data.

## 5. Third-party libraries

HaronTV uses open-source libraries (e.g. VLC for video, JSch for SFTP). Text and QR recognition run on the device. The author does not share your data with library developers.

## 6. Children

The app collects no data about anyone, including children.

## 7. Changes

When this policy changes, the date at the top is updated.

## 8. Contact

vampilenna@gmail.com · https://github.com/Dolgoibimus/HaronTV
