
Primeiro baixe o drive [Aqui ](https://www.fischl.de/usbasp/usbasp.2011-05-28.tar.gz) e depois descompacte e entre no diretodio pelo terminal.


```
sudo apt install avrdude
```
```
avr -F -B 1500khz -c usbasp -p atmega328p -U lock:r:lock.hex:h
```

```
cd ~/Download/usbasp.2015-05-28/bin/linux-nonroot
```

```
install-rule + sudo cp 99-USBasp-rules /etc/udev/rules.d/99-USBasp.rules
```

```
avr -F -B 1500khz -c usbasp -p atmega328p -U lock:r:lock.hex:h
```
