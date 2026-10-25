<a href="https://nevpn.app">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.png">
    <img src="assets/banner-light.png" alt="NE.VPN — VPN-клиент для Android и Mac, который подключается при белых списках" width="100%">
  </picture>
</a>

<h1 align="center">NE.VPN — VPN-клиент для Android и Mac</h1>

<p align="center">Бесплатный VPN для Android и macOS, который подключается при белых списках · Free VPN client for Android and Mac</p>

<p align="center">
  <a href="https://github.com/FijshH/nevpn-releases/releases/latest"><img alt="Последняя версия для Android" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub.com%2FFijshH%2Fnevpn-releases%2Freleases%2Flatest%2Fdownload%2Fupdate.json&query=%24.android.versionName&label=Android&color=15803d&style=flat-square&logo=android&logoColor=white"></a>
  <a href="https://nevpn.app/mac/"><img alt="Последняя версия для Mac" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fgithub.com%2FFijshH%2Fnevpn-releases%2Freleases%2Flatest%2Fdownload%2Fupdate.json&query=%24.macos.version&label=macOS&color=15803d&style=flat-square&logo=apple&logoColor=white"></a>
  <a href="https://github.com/FijshH/nevpn-releases/releases"><img alt="Скачивания" src="https://img.shields.io/github/downloads/FijshH/nevpn-releases/total?label=%D1%81%D0%BA%D0%B0%D1%87%D0%B8%D0%B2%D0%B0%D0%BD%D0%B8%D1%8F&color=000&style=flat-square"></a>
  <img alt="Android 8.0+" src="https://img.shields.io/badge/Android-8.0%2B-000?style=flat-square&logo=android&logoColor=white">
  <img alt="macOS 15+, Apple silicon и Intel" src="https://img.shields.io/badge/macOS-15%2B%20%C2%B7%20Apple%20silicon%20%26%20Intel-000?style=flat-square&logo=apple&logoColor=white">
  <a href="https://nevpn.app"><img alt="nevpn.app" src="https://img.shields.io/badge/nevpn.app-000?style=flat-square"></a>
</p>

<p align="center">
  <a href="https://github.com/FijshH/nevpn-releases/releases/latest"><b>Скачать для Android (APK)</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://nevpn.app/download/mac"><b>Скачать для Mac (.pkg)</b></a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://nevpn.app">Сайт</a>
  &nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="#english">English</a>
</p>

**NE.VPN** — бесплатный VPN-клиент для Android и macOS. Одна кнопка, подписки любых провайдеров и поддержка OpenFlux, который подключается, когда мобильный интернет на белых списках и обычный VPN не работает. Здесь лежат все версии приложения: [APK для Android](https://github.com/FijshH/nevpn-releases/releases/latest) и [установщик для Mac](https://nevpn.app/download/mac). Новые версии приложение найдёт и поставит само — на телефоне и на Mac.

<p align="center">
  <img src="assets/screens.png" alt="Экраны NE.VPN: подключено, светлая тема, несколько подписок, настройки" width="100%">
</p>

## Возможности

- **Белые списки.** Когда оператор пропускает только разрешённые сайты, обычный VPN не подключается. NE.VPN умеет OpenFlux: добавьте ссылку `openflux://` провайдера или своего сервера, и если прямой путь закрыт, канал сам перейдёт на запасной.
- **Любая подписка.** Ссылка-подписка любого провайдера, отдельные ссылки, ключ Amnezia `vpn://` или файл `.conf`. Подписок сколько угодно, между ними — свайп.
- **Протоколы:** VLESS (Reality, XHTTP, WS, gRPC), VMess, Trojan, Shadowsocks, Hysteria2, TUIC, AnyTLS, AmneziaWG до 3.1, WireGuard, OpenFlux.
- **Два ядра.** sing-box по умолчанию, Xray-core — переключателем в настройках.
- **Россия мимо VPN.** Банки, Госуслуги, Яндекс, VK и маркетплейсы работают напрямую и не видят адрес сервера. Список приложений можно поменять.
- **Пинг до каждого сервера** ещё до подключения: ICMP или время TCP-соединения.
- **Обновляется само.** О новой версии приходит уведомление; если сервер обновлений закрыт, приложение скачает её через VPN.
- **Продление в приложении.** «Продлить» открывает страницу оплаты провайдера, «Кабинет» — его личный кабинет. Приложение напомнит, когда подписка подходит к концу.
- **Плитка в шторке, постоянная VPN и автоподключение.**
- **Планшеты и раскладные телефоны:** кнопка слева, подписки справа, по несколько в ряд.

<p align="center">
  <img src="assets/tablet.png" alt="NE.VPN на планшете: кнопка подключения слева, две подписки справа" width="100%">
</p>

## NE.VPN для Mac

Те же подписки и профили, что на Android, в маленьком окне и строке меню. macOS 15 Sequoia, 26 Tahoe и 27, Apple silicon и Intel. Подробно — [nevpn.app/mac](https://nevpn.app/mac/).

<p align="center">
  <img src="assets/mac.png" alt="NE.VPN для Mac: подключено в тёмной и светлой теме, несколько подписок вкладками, настройки" width="100%">
</p>

- **Строка меню.** Подключение, смена профиля и пинг — из значка «ne» вверху экрана. Значок в Dock можно выключить.
- **Подписки вкладками.** Листайте двумя пальцами, переключайтесь ⌃⇥ или ⌘1…9, меняйте порядок перетаскиванием.
- **Liquid Glass** в macOS 26 и новее, привычный вид macOS 15 в Sequoia; светлая и тёмная тема — как в системе.
- **Те же протоколы и белые списки:** VLESS Reality и XHTTP, Hysteria2, AmneziaWG, WireGuard, OpenFlux и другие, ядро sing-box.
- **Россия мимо VPN:** российские сайты и адреса открываются напрямую.
- **Страница провайдера** с продлением и кабинетом, напоминания об окончании подписки.
- **Обновляется само** в один клик; английский и русский интерфейс.

## Подписки из других приложений и свой сервер

NE.VPN читает те же форматы, что и другие клиенты, поэтому подписку менять не нужно:

- **Happ, v2rayNG, Hiddify, NekoBox, Streisand:** скопируйте ссылку-подписку или ссылки `vless://`, `vmess://`, `trojan://`, `ss://`, `hysteria2://` и вставьте через **+**. Зашифрованные ссылки `happ://crypt…` открывает только Happ — попросите у провайдера обычную ссылку.
- **AmneziaVPN и AmneziaWG:** ключ `vpn://`, ссылка `awg://` или файл `.conf`, AmneziaWG до версии 3.1.
- **WireGuard:** файл `.conf` или ссылка `wireguard://`.
- **Свой сервер на 3x-ui, Marzban или Remnawave:** ссылка-подписка панели (обычный текст, base64, конфиг sing-box или Xray). Срок подписки приложение показывает, если панель его сообщает.

## Установка на Android

1. Откройте [последний релиз](https://github.com/FijshH/nevpn-releases/releases/latest) и скачайте APK (какой — в таблице ниже).
2. Откройте файл. Android попросит разрешить установку из браузера — разрешите один раз.
3. В приложении нажмите **+** и вставьте ссылку-подписку, отдельные ссылки или ключ.
4. Нажмите кнопку подключения. Android один раз спросит разрешение на VPN.

Root не нужен. Нужен Android 8.0 или новее.

### Какой APK выбрать

| Файл | Для чего |
|---|---|
| `nevpn-<версия>-arm64-v8a.apk` | Почти все телефоны и планшеты последних лет. Если не знаете — берите этот |
| `nevpn-<версия>-armeabi-v7a.apk` | Старые 32-битные телефоны |
| `nevpn-<версия>-x86_64.apk` | Эмуляторы и устройства на Intel/AMD |
| `nevpn-<версия>.apk` | Универсальный: подходит всем, но весит втрое больше |

## Установка на Mac

1. Скачайте [установщик NE.VPN .pkg](https://nevpn.app/download/mac) — один файл для Apple silicon и Intel. Все версии для Mac — [в релизах `macos-…`](https://github.com/FijshH/nevpn-releases/releases?q=macos&expanded=true).
2. Откройте его. Если macOS пишет, что не может проверить установщик: Системные настройки → Конфиденциальность и безопасность → «Всё равно открыть». Это нужно один раз.
3. NE.VPN появится в «Программах» и откроется сам. При первом подключении macOS попросит включить NE.VPN в «Объектах входа и расширениях»: туннель работает как системная служба.
4. Нажмите **+**, вставьте ссылку-подписку или ключ и подключайтесь. Дальше приложение обновляется само.

Без установщика: [образ диска .dmg](https://nevpn.app/download/mac-dmg), перетащите NE.VPN в «Программы» (macOS спросит разрешение дважды). Файл `.zip` в релизе — то, из чего приложение обновляется.

### Проверка файла

Все версии подписаны одним ключом, поэтому Android не поставит поверх приложения APK с другой подписью. SHA-256 сертификата подписи:

```text
1a8a04777f3301cf7ad24274c55640528e36d347d744f9fa82c47416802d35ca
```

Проверить подпись и сам файл (суммы SHA-256 каждого APK лежат в `update.json` релиза и на [nevpn.app](https://nevpn.app)):

```bash
apksigner verify --print-certs nevpn-*.apk
shasum -a 256 nevpn-*.apk
```

## Вопросы

<details>
<summary><b>Приложение бесплатное?</b></summary>
<br>
Да. Это клиент: он подключается к серверам вашей подписки — от провайдера или своего сервера.
</details>

<details>
<summary><b>Есть версия для Mac? А для iPhone и Windows?</b></summary>
<br>
Для Mac — да: macOS 15 и новее, Apple silicon и Intel, <a href="https://nevpn.app/mac/">nevpn.app/mac</a>. Для iPhone, iPad и Windows пока нет.
</details>

<details>
<summary><b>Почему не в Google Play и App Store?</b></summary>
<br>
Приложение распространяется отсюда — APK для Android и установщик для Mac — и обновляется само. Так новые версии доходят до всех сразу и не зависят от магазина.
</details>

<details>
<summary><b>Что такое белые списки и как VPN работает при них?</b></summary>
<br>
Белые списки — режим, в котором мобильный оператор пропускает только заранее разрешённые сайты. Обычные VPN в нём не подключаются. Работают профили OpenFlux: если ваш провайдер их даёт, включите такой, когда мобильный интернет перестал открывать что-либо, кроме российских сайтов. Канал сам перейдёт на запасной путь, если прямой закрыт.
</details>

<details>
<summary><b>Какие подписки подходят?</b></summary>
<br>
Ссылка-подписка (обычный текст, base64, конфиг sing-box или Xray) или ссылки <code>vless://</code>, <code>vmess://</code>, <code>trojan://</code>, <code>ss://</code>, <code>hysteria2://</code>, <code>tuic://</code>, <code>anytls://</code>, <code>awg://</code>, <code>wireguard://</code>, <code>openflux://</code>, ключ <code>vpn://</code> или файл <code>.conf</code>. Строки, которые приложение не понимает, оно пропускает.
</details>

<details>
<summary><b>Чем VPN-клиент отличается от VPN-сервиса?</b></summary>
<br>
Клиент — приложение, которое подключается к серверам. Серверы и подписку даёт провайдер или ваш собственный сервер. NE.VPN — клиент: он бесплатный и работает с подпиской любого провайдера.
</details>

<details>
<summary><b>Какой телефон нужен?</b></summary>
<br>
Android 8.0 и новее, телефон, планшет или раскладной. Root не нужен. Если не знаете, какой APK выбрать, берите <code>arm64-v8a</code>: он для почти всех телефонов.
</details>

<details>
<summary><b>Какой Mac нужен и почему macOS спрашивает разрешение?</b></summary>
<br>
Любой Mac с macOS 15 Sequoia, 26 Tahoe или 27, на Apple silicon или Intel. macOS спрашивает один раз, когда открываете установщик (приложение не из App Store), и один раз при первом подключении — чтобы включить службу, которая поднимает VPN.
</details>

<details>
<summary><b>Банк не открывается с VPN. Что делать?</b></summary>
<br>
Российские приложения уже работают мимо VPN. Если какое-то нет, в настройках откройте «Приложения вне VPN» и отметьте его.
</details>

<details>
<summary><b>Нашли ошибку?</b></summary>
<br>
<a href="https://github.com/FijshH/nevpn-releases/issues/new">Откройте issue</a>: модель телефона или Mac, версия Android или macOS, версия приложения (Настройки → О приложении) и что происходит.
</details>

---

<a id="english"></a>

## English

**NE.VPN** is a free VPN client for Android and macOS. One button, subscriptions from any provider, and OpenFlux support, which connects when mobile data is restricted to a whitelist and ordinary VPNs fail. This repository holds every release of the app, [APKs for Android](https://github.com/FijshH/nevpn-releases/releases/latest) and [the Mac installer](https://nevpn.app/download/mac); the app finds and installs new ones by itself.

- **Whitelist lockdowns:** add an `openflux://` link from your provider or your own server; the channel falls back to another path by itself when the direct one is closed.
- **Any subscription:** subscription links, single links, Amnezia `vpn://` keys and `.conf` files, as many as you like.
- **Protocols:** VLESS (Reality, XHTTP, WS, gRPC), VMess, Trojan, Shadowsocks, Hysteria2, TUIC, AnyTLS, AmneziaWG up to 3.1, WireGuard, OpenFlux.
- **Two engines:** sing-box by default, Xray-core with a switch in the settings.
- **Russian apps and sites stay outside the VPN**, so banks and Gosuslugi keep working.
- **Renew from the app:** the renew button opens your provider's payment page, the account button its account page; a reminder comes before the subscription runs out.
- Ping to every server, self-update, quick settings tile, always-on VPN, tablets and foldables.
- **On the Mac** (macOS 15 Sequoia and later, Apple silicon and Intel): the same subscriptions and profiles in a small window and the menu bar, subscriptions as tabs, Liquid Glass on macOS 26, English and Russian. More at [nevpn.app/en/mac](https://nevpn.app/en/mac/).

### Install on Android

Download the `arm64-v8a` APK from the [latest release](https://github.com/FijshH/nevpn-releases/releases/latest) (`armeabi-v7a` for old 32-bit phones, `x86_64` for emulators, or the universal one), open it, allow installs from your browser once, tap **+** in the app and paste your subscription. Android 8.0 or later, no root.

### Install on a Mac

Download the [.pkg installer](https://nevpn.app/download/mac) (one file for Apple silicon and Intel) and open it. If macOS says it cannot check the installer: System Settings → Privacy & Security → Open Anyway, once. NE.VPN goes to Applications and opens; on the first connect macOS asks to allow it in Login Items & Extensions, since the tunnel runs as a system service. Click **+**, paste your subscription and connect. A [.dmg](https://nevpn.app/download/mac-dmg) is there too; every Mac version is in the [`macos-…` releases](https://github.com/FijshH/nevpn-releases/releases?q=macos&expanded=true).

### Coming from another app

Subscriptions and links from Happ, v2rayNG, Hiddify, NekoBox and Streisand work as they are, and so do AmneziaVPN `vpn://` keys, WireGuard and AmneziaWG `.conf` files and subscription links from 3x-ui, Marzban and Remnawave panels. Happ's encrypted `happ://crypt…` links open in Happ only: ask your provider for the plain link.

### FAQ

**Is it free?** Yes. It is a client: it connects to the servers of your subscription, from a provider or your own server.

**What is a whitelist lockdown?** A mode in which a mobile carrier lets through approved sites only. Ordinary VPNs do not connect in it; OpenFlux profiles do, and fall back to another path by themselves when the direct one is closed.

**Is there an iPhone or Windows version?** Not yet: Android and macOS today.

**Why not Google Play or the App Store?** The app ships from this repository, a signed APK for Android and an installer for the Mac, and updates itself, so new versions reach everyone at once. Android will not install an APK with another signature over it, and the Mac app installs only updates signed by the same developer.

**Found a bug?** [Open an issue](https://github.com/FijshH/nevpn-releases/issues/new) with the phone or Mac model, Android or macOS version and app version.

<p align="center"><sub>VPN для Android · VPN для Mac · VPN для macOS · VPN-клиент · обход белых списков · VLESS Reality · XHTTP · VMess · Trojan · Shadowsocks · Hysteria2 · TUIC · AnyTLS · AmneziaWG · WireGuard · OpenFlux · sing-box · Xray-core · Android VPN client · Mac VPN client · macOS VPN · APK · <a href="https://nevpn.app">nevpn.app</a></sub></p>
