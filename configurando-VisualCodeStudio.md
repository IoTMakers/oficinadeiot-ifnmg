Configrando o ambiente 

Instalar o PlatformIO.

Via terminal linux digitar os seguintes comandos.
```
sudo mkdir -p  /etc/udev/rules.d && cd /etc/udev/rules.d
sudo wget https://raw.githubusercontent.com/platformio/platformio-core/develop/scripts/99-platformio-udev.rules
sudo udevadm control --reload-rules
sudo udevadm trigger
```
