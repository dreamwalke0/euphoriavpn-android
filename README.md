<div align="center">

# Euphoria VPN

**Современный VPN-клиент для Android на базе Xray-core**

</div>

## Возможности

- VPN через Android VpnService
- Запуск Xray-core
- Импорт подписок и конфигов
- Автообновление подписок
- Пинг и автовыбор сервера
- Split Tunnel
- Kill Switch
- Настройка DNS
- Статистика и логи

## Поддерживаемые протоколы

`VLESS` `VMess` `Trojan` `Shadowsocks` `SOCKS` `HTTP`

## Поддерживаемые транспорты

`Reality` `TLS` `TCP` `WebSocket` `gRPC` `HTTPUpgrade` `SplitHTTP` `xHTTP` `QUIC` `HTTP/2` `MUX` `FakeDNS`

## Готовые режимы маршрутизации

- Умный РФ
- Обход блокировок
- Мессенджеры
- Торренты
- Игры

## Поддержка Android

- Android 7.0+ (API 24)
- Target SDK 36
- arm64-v8a
- x86_64 (эмуляторы)

## Сборка

```bash
./gradlew assembleRelease bundleRelease
```

## Версия

**1.0.0 Beta**
