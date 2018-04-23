# cpuminer-multi-ubuntu-service
Service file to autostart cpuminer multi to mine cryptocurrencies on Ubuntu 16.04


# Instructions


Put this file in /lib/systemd/system/

Don't forget to set your pool and wallet address!


then apply the following commands:


sudo systemctl daemon-reload


sudo systemctl enable cpuminer-multi.service


sudo systemctl start cpuminer-multi.service
