# AUTOBRILLO

	Probado solamente en Linux Mint ***

	Usuarios de Arch y derivados es posible tengan que hacer un pequeño ajuste porque aparentemente dentro de /sys/class/backlight/ en vez de estar el enlace simbólico al archivo al archivo de backlight hay una carpeta que lo contiene:
	
	https://wiki.archlinux.org/title/Backlight	

# Instalación

	git clone https://github.com/boctulus/autobrillo.git
	cd autobrillo
	sudo cp autobrillo /usr/bin/
	sudo cp autobrillo.service /etc/systemd/system/ 


