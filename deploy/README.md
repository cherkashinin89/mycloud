# Развёртывание MyCloud

## Требования

- **ОС:** Debian 12 / Ubuntu 22.04 LTS
- **Пользователь:** `deploy` с `sudo`
- **Пакеты:** `git`, `python3`, `python3-venv`
- **`myframework`** должен быть **установлен** (**общая БД**, **общая статика**)

## Быстрый старт

```bash
cd /home/deploy/apps
git clone git@github.com:cherkashinin89/mycloud.git
cd mycloud
cp deploy/env.example .env
nano .env
chmod +x deploy/setup.sh
./deploy/setup.sh