sudo socat tcp4-LISTEN:80,reuseaddr,fork,keepalive,bind=127.0.0.1 SOCKS4A:127.0.0.1:adress.onion:80,socksport=9050
