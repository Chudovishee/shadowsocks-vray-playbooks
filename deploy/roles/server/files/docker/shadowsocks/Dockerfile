FROM shadowsocks/shadowsocks-libev:latest

USER 0

RUN wget -cq -O /root/v2ray-plugin.tar.gz https://github.com/shadowsocks/v2ray-plugin/releases/download/v1.3.1/v2ray-plugin-linux-amd64-v1.3.1.tar.gz \
  && tar xvzf /root/v2ray-plugin.tar.gz -C /root \
  && mv /root/v2ray-plugin_linux_amd64 /usr/local/bin/v2ray-plugin \
  && rm -f /root/v2ray-plugin.tar.gz

#USER 777