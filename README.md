	apt-get install pkg-config libnl-3-dev libnl-genl-3-dev libpcap-dev 

	git clone https://github.com/aircrack-ng/mdk4
	cd mdk4
	make
	sudo make install
	# Using Arch Linux (and derived) append `CC=clang` after any `make` in commands. 
