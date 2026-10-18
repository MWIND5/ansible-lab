# ansible-lab

Ansible playbook для установки и конфигурации nginx.

## Запуск

    ansible-playbook -i hosts.ini playbook.yml

## Что делает

- Устанавливает nginx через apt
- Запускает и включает автозапуск
- Копирует index.html
- Перезапускает nginx при изменении index.html

## Проверка

    curl http://localhost