AUTO SCRIPT SSH WG TR SS SSR VLESS XRAY DEBIAN 9 & 10
1. apt-get update && apt-get upgrade -y && update-grub && sleep 2 && reboot
2. sysctl -w net.ipv6.conf.all.disable_ipv6=1 && sysctl -w net.ipv6.conf.default.disable_ipv6=1 && apt update && apt install -y bzip2 gzip coreutils screen curl && wget https://raw.githubusercontent.com/aryprabow/Script/main/setup.sh && chmod +x setup.sh && screen -S setup ./setup.sh
