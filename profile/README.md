<div align="center">

<picture>
  <source media="(prefers-color-scheme: light)" srcset="logo-light.svg">
  <img src="logo.svg" alt="raycat" width="150">
</picture>

### Менеджер VPN-подписок для Linux-серверов

Для нужных контейнеров, всего сервера или домашней сети.

[**raycat**](https://github.com/raycat-app/raycat) · [Выпуски](https://github.com/raycat-app/raycat/releases) · [Обсуждения](https://github.com/raycat-app/raycat/discussions)

[![Звёзды](https://img.shields.io/github/stars/raycat-app/raycat?style=flat-square&label=звёзды&color=2d333b)](https://github.com/raycat-app/raycat)
[![Версия](https://img.shields.io/github/v/release/raycat-app/raycat?include_prereleases&style=flat-square&label=версия&color=2d333b)](https://github.com/raycat-app/raycat/releases)
[![Лицензия](https://img.shields.io/badge/лицензия-MIT-2d333b?style=flat-square)](https://github.com/raycat-app/raycat/blob/main/LICENSE)

</div>

## Навигация

<table>
<tr><th width="300">Раздел</th><th width="700">Что там</th></tr>
<tr><td><a href="https://github.com/raycat-app/raycat"><b>Репозиторий</b></a></td><td>исходный код и документация</td></tr>
<tr><td><a href="https://github.com/raycat-app/raycat/releases/latest"><b>Последний выпуск</b></a></td><td>архивы для x86_64, arm64 и armv7, контрольные суммы</td></tr>
<tr><td><a href="https://github.com/raycat-app/raycat/pkgs/container/raycat"><b>Образ Docker</b></a></td><td><code>ghcr.io/raycat-app/raycat</code>, для процессоров без AES — тег <code>latest-noaes</code></td></tr>
<tr><td><a href="https://github.com/raycat-app/raycat#установка"><b>Установка</b></a></td><td>в Docker или службой на сервере</td></tr>
<tr><td><a href="https://github.com/raycat-app/raycat#режимы-работы"><b>Режимы работы</b></a></td><td>выбранные контейнеры, весь сервер, отдельные программы, домашняя сеть</td></tr>
<tr><td><a href="https://github.com/raycat-app/raycat#настройки"><b>Настройки</b></a></td><td>один файл с пояснениями к каждому параметру</td></tr>
<tr><td><a href="https://github.com/raycat-app/raycat/discussions"><b>Обсуждения</b></a></td><td>вопросы и предложения</td></tr>
<tr><td><a href="https://github.com/raycat-app/raycat/issues/new?template=bug.yml"><b>Сообщить об ошибке</b></a></td><td>не публикуйте ссылку подписки</td></tr>
<tr><td><a href="https://github.com/raycat-app/raycat/security/advisories/new"><b>Уязвимость</b></a></td><td>сообщить приватно</td></tr>
</table>

## Быстрый старт

```sh
# служба на сервере
curl -fsSL https://raw.githubusercontent.com/raycat-app/raycat/main/deploy/install.sh | sudo sh

# образ Docker
docker pull ghcr.io/raycat-app/raycat
```

Дальше — подключение подписки и выбор режима в [README проекта](https://github.com/raycat-app/raycat#установка).

<details>
<summary><b>English</b></summary>

<br>

**A VPN subscription manager for Linux servers.** For chosen containers, the whole server or your home network.

[Repository](https://github.com/raycat-app/raycat) · [Documentation](https://github.com/raycat-app/raycat/blob/main/.github/README.en.md) · [Latest release](https://github.com/raycat-app/raycat/releases/latest) · [Docker image](https://github.com/raycat-app/raycat/pkgs/container/raycat) · [Discussions](https://github.com/raycat-app/raycat/discussions)

</details>
