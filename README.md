# Keenetic-Netcraze

> Коллекция готовых списков доменов и IP-адресов для **KeeneticOS** и
> **Netcraze** для выборочной маршрутизации трафика через VPN.

## Возможности

-   🚀 Выборочная маршрутизация через VPN
-   🌐 Маршрутизация по доменам
-   📡 IPv4 Fallback для сервисов
-   🔐 Поддержка OpenConnect VPN
-   📦 Готовые списки для популярных сервисов

## Структура репозитория

``` text
Keenetic-Netcraze/
│
├── YouTube/
│   ├── domains.list
│   └── ipv4.list
├── Telegram/
│   ├── domains.list
│   └── ipv4.list
├── Discord/
│   ├── domains.list
│   ├── voice-domains.list
│   ├── ipv4-cloudflare.list
│   └── ipv4-google-rtc.list
├── GitHub/
│   └── domains.list
├── Figma/
│   ├── domains.list
│   └── ipv4.list
├── WhatsApp/
│   └── domains.list
├── Facebook-Instagram/
│   └── domains.list
├── Snapchat/
│   ├── domains.list
│   └── ipv4.list
├── Cloudflare/
│   ├── domains.list
│   └── ipv4.list
└── AWS-CloudFront/
    └── ipv4.list
```

## Что содержится в репозитории

Каждый каталог содержит один или несколько файлов:

-   **domains.list** --- список доменных имён для DNS-маршрутизации.
-   **ipv4.list** --- резервный список IPv4-подсетей, если приложение
    обращается напрямую по IP.
-   Дополнительные файлы (`voice-domains.list`, `ipv4-cloudflare.list` и
    так далее) предназначены для отдельных сценариев маршрутизации.

## Как использовать

1.  Откройте **Сетевые правила → Маршрутизация → Маршруты DNS**.
2.  Создайте новый список доменных имён или IP-адресов.
3.  Скопируйте содержимое соответствующего файла из репозитория.
4.  Создайте правило маршрутизации и выберите VPN-интерфейс.
5.  Повторите для остальных сервисов.

После этого только выбранные сервисы будут работать через VPN, а
остальной интернет останется у вашего провайдера.

## Поддерживаемые сервисы

-   YouTube
-   Telegram
-   Discord
-   GitHub
-   Figma
-   WhatsApp
-   Facebook
-   Instagram
-   Snapchat
-   Cloudflare
-   AWS CloudFront

## Обновление списков

Инфраструктура сервисов регулярно меняется, поэтому рекомендуется
периодически обновлять списки из данного репозитория.

## Предложения и ошибки

Если обнаружили отсутствующий домен, IP-адрес или сервис перестал
работать --- создайте Issue или Pull Request.

Любая помощь приветствуется!

## Полезные ссылки

### 👉 **[Подписаться на Telegram-канал DevOpsInTapki](https://t.me/devopsintapki)**
### 👉 **[VPS + домен + сертификат](https://t.me/devopsintapki/229)**
### 👉 **[Настраиваем OpenConnect - ocserv.conf](https://t.me/devopsintapki/232)**
### 👉 **[NAT, Firewall](https://t.me/devopsintapki/233)**
### 👉 **[Первое подключение](https://t.me/devopsintapki/234)**
### 👉 **[Маршрутизация](https://t.me/devopsintapki/244)**

## Лицензия

MIT License