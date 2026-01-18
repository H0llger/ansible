Role: basic-configuration
========================

Базовая настройка Linux-сервера:
- обновление системы
- установка common-пакетов
- bash-алиасы

Поддерживаемые ОС: Debian/Ubuntu

## Variables
- bashrc_user
- bashrc_home
- bash_aliases

## Example
```yaml
roles:
  - basic-configuration