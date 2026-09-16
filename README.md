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
├── Apple - Domains
│   └── domains.list
├── Bybit - Domains
│   └── domains.list
├── Bybit - IP Fallback
│   └── ipv4.list
├── Claude - Domains
│   └── domains.list
├── Claude - IP Fallback
│   └── ipv4.list
├── Cursor - Domains
│   └── domains.list
├── Discord - Core
│   └── domains.list
├── Discord - IP Fallback
│   └── ipv4.list
├── Discord - Voice
│   └── domains.list
├── Facebook Meta - Domains
│   └── domains.list
├── Facebook Meta - IP
│   └── ipv4.list
├── Figma - Domains
│   └── domains.list
├── Figma - IP Fallback
│   └── ipv4.list
├── Gemini Antigravity - Domains
│   └── domains.list
├── Gemini Antigravity - IP Fallback
│   └── ipv4.list
├── GitHub - Domains
│   └── domains.list
├── Hugging Face - Domains
│   └── domains.list
├── Hugging Face - IP Fallback
│   └── ipv4.list
├── Keenetic - Domains
│   └── domains.list
├── Loom - Domains
│   └── domains.list
├── Mux - Domains
│   └── domains.list
├── OpenAI - Domains
│   └── domains.list
├── OpenAI - IP Fallback
│   └── ipv4.list
├── OpenAI - Voice IP
│   └── ipv4.list
├── README.md
├── Skool - Domains
│   └── domains.list
├── Snapchat - Domains
│   └── domains.list
├── Snapchat - IP Fallback
│   └── ipv4.list
├── Telegram - Domains
│   └── domains.list
├── Telegram - IP
│   └── ipv4.list
├── WhatsApp Meta - Domains
│   └── domains.list
├── WhatsApp Meta - IP
│   └── ipv4.list
├── YouTube - Domains
│   └── domains.list
└── YouTube - IP Fallback
    └── ipv4.list
```

## Что содержится в репозитории

Каждый каталог содержит один или несколько файлов:

-   **domains.list** --- список доменных имён для DNS-маршрутизации.
-   **ipv4.list** --- резервный список IPv4-подсетей, если приложение
    обращается напрямую по IP.

## Как использовать

1.  Откройте **Сетевые правила → Маршрутизация → Маршруты DNS**.
2.  Создайте новый список доменных имён или IP-адресов.
3.  Скопируйте содержимое соответствующего файла из репозитория.
4.  Создайте правило маршрутизации и выберите VPN-интерфейс.
5.  Повторите для остальных сервисов.

После этого только выбранные сервисы будут работать через VPN, а
остальной интернет останется у вашего провайдера.

## Поддерживаемые сервисы

-   Apple
-   Bybit
-   Claude
-   Cursor
-   Discord
-   Facebook
-   Figma
-   Google AI
-   GitHub
-   Hugging Face
-   Keenetic
-   Loom
-   Mux
-   OpenAI
-   Skool
-   Snapchat
-   Telegram
-   WhatsApp
-   Youtube

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