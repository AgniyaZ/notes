# Сети linux

## Утилиты
### ifconfig

- ifconfig - просмотр настроек сетевых интерфейсов
- ifconfig em1 192.168.1.5/24 - назначить ip-адрес на интерфейс 

### scapy (https://habr.com/ru/post/208786/)
инструмент создания и работы с сетевыми пакетами

- lsc() - список доступных функций
- help(имя_функции) - информация о функции
- ls() - список поддерживаемых протоколов
- ls(имя_протокола) - информация о параметрах для выбранного протокола
- ls(имя_пакета) - информация о созданном пакете
  
Cетевой пакет разделяется на слои, и каждый слой представляется как экземпляр объекта.
Собранный пакет в упрощенном виде может выглядеть как: Ether()/IP()/TCP()/”App Data”
