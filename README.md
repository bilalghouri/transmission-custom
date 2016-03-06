# transmission-custom
modified transmissionbt for lse

#To build from source 
https://trac.transmissionbt.com/wiki/Building

    apt-get install ca-certificates libcurl4-openssl-dev libssl-dev pkg-config build-essential checkinstall
    checkinstall
    CFLAGS="-Os -march=native"
    ./configure --enable-cli --enable-daemon --with-systemd-daemon
    make
    checkinstall

checkinstall will make a .deb file as well.
