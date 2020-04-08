FROM jpillora/dnsmasq

ARG SERVER_ADDR

ADD dnsmasq.conf /etc/dnsmasq.conf
RUN echo "address=/.company/${SERVER_ADDR}" >> /etc/dnsmasq.conf