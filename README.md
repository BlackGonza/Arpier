# Arpier

Arpier - это скрипт на Bash для выполнения атаки ARP Spoofing. Он создает поддельную точку доступа (Rogue AP) и перенаправляет сетевой трафик жертвы через ваш компьютер, позволяя перехватывать данные и атаковать уязвимости в сети.

## Функции

- Создание фейковой HTML страницы обновления прошивки для перехвата паролей
- Проверка ввода IP-адресов для жертвы и шлюза
- Автоматическое включение IP forwarding
- Запуск ARP Spoofing для перенаправления сетевого трафика
- Очистка настроек после завершения скрипта

## Использование

1. Склонируйте репозиторий:
<pre style="animation: blink 1s infinite;">
git clone <span style="color: blue;">https://github.com/BlackGonza/arpier.git</span>
<span style="color: red;">cd</span> arpier
</pre>

<style>
@keyframes blink {
  50% {
    opacity: 0;
  }
}
</style>

2. Запустите скрипт:
<pre>
sudo bash arpier.sh
</pre>
3. Введите запрошенную информацию (интерфейс, IP-адреса жертвы и шлюза).

4. Наблюдайте за выводом скрипта и перехватываемыми данными.

## Требования

- Linux (для выполнения с правами суперпользователя)
- Bash
- arpspoof

## Безопасность

Пожалуйста, используйте этот скрипт только в законных целях и с согласия владельца сети. Неправомерное использование этого скрипта может повлечь за собой юридические последствия.

## Авторы

BlackGonza - создание скрипта

## Лицензия

Этот проект лицензирован под MIT License - см. файл [LICENSE](LICENSE) для получения дополнительной информации.
