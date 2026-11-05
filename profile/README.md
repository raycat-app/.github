<div align="center">

<picture>
  <source media="(prefers-color-scheme: light)" srcset="logo-light.svg">
  <img src="logo.svg" alt="raycat" width="150">
</picture>

### Открытые инструменты, чтобы VPN работал на сервере сам

Подключаете подписку один раз, а дальше нужные контейнеры, весь сервер или домашняя сеть выходят в интернет через неё.

[**raycat**](https://github.com/raycat-app/raycat) · [Выпуски](https://github.com/raycat-app/raycat/releases) · [Обсуждения](https://github.com/raycat-app/raycat/discussions)

[![Звёзды](https://img.shields.io/github/stars/raycat-app/raycat?style=flat-square&label=звёзды&color=2d333b)](https://github.com/raycat-app/raycat)
[![Версия](https://img.shields.io/github/v/release/raycat-app/raycat?include_prereleases&style=flat-square&label=версия&color=2d333b)](https://github.com/raycat-app/raycat/releases)
[![Лицензия](https://img.shields.io/badge/лицензия-MIT-2d333b?style=flat-square)](https://github.com/raycat-app/raycat/blob/main/LICENSE)


<br>

<img src="tui.png" alt="raycat tui" width="820">

</div>

| Что идёт через VPN | Как это работает |
| --- | --- |
| **Отдельные контейнеры** | raycat в Docker, остальной сервер работает как обычно |
| **Весь сервер** | raycat службой, без туннеля трафик не выходит наружу |
| **Отдельные программы** | прокси HTTP и SOCKS5 на `127.0.0.1:7890` |
| **Домашняя сеть** | телевизор или приставка выходят через сервер |

<details>
<summary><b>English</b></summary>

<br>

raycat keeps a VPN subscription running on a Linux server. Chosen containers, the whole server or your home network go online through it, without configuring each application. See the [repository](https://github.com/raycat-app/raycat/blob/main/README.en.md).

</details>
