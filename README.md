# Windows приложение для мониторинг служб Linux системы с помощью SSH подключение. 

Для корректной работы программы:
```
sudo apt-get install lm-sensors -y
```
```
sudo apt-get install fail2ban -y
```
```
> sudo visudo
После строки root ALL=(ALL:ALL) NOPASSWD: ALL добавьте:
> %username% ALL=(ALL:ALL) NOPASSWD: ALL
```
- Вместо ALL можно вписать только требуемые программой команды
