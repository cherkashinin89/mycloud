# Развёртывание MyCloud

## Требования

- **ОС:** Debian 12 / Ubuntu 22.04 LTS
- **Пользователь:** `admin` с `sudo`
- **Пакеты:** `git`, `python3.11`, `python3.11-venv`
- **`myframework`** должен быть **установлен** (**общая БД**, **общая статика**)

## Быстрый старт

```bash
cd /home/admin/apps
git clone git@github.com:cherkashinin89/mycloud.git
cd mycloud
cp deploy/env.example .env
nano .env
chmod +x deploy/setup.sh
./deploy/setup.sh