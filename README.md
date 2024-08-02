## OpenVPN paranoid installer
### Обновления от 30.07.2024
 - Обновлен EasyRSA до версии 3.2.0
 - Изменен размер DH ключа до 2048

### Описание

OpenVPN установщик для Debian, Ubuntu и CentOS.

Этот скрипт позволит вам поднять свой собственный VPN-сервер не более чем за минуту, даже если вы раньше не использовали OpenVPN.

Этот проект является изначально форком <a href="https://github.com/Nyr/openvpn-install" target="_blank">openvpn-install</a> с упором на безопасность.

Я же форкнул из <a href="https://github.com/cryptopunks/openvpn_paranoid_installer">https://github.com/cryptopunks/openvpn_paranoid_installer</a> :)

### Установка
Выполните команду и следуйте дальнейшим инструкциям:

`wget https://raw.githubusercontent.com/rsgrinko/openvpn_paranoid_installer/master/openvpn_paranoid_installer.sh --no-check-certificate -O openvpn_paranoid_installer.sh; bash openvpn_paranoid_installer.sh`

После завершения вы можете запустить эту команду снова, чтобы добавить больше пользователей, удалить некоторых из них или даже полностью удалить OpenVPN.

