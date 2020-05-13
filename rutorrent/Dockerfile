FROM linuxserver/rutorrent:v3.9-ls54
ENV TZ='America/New_York'
RUN wget https://github.com/alexcreek/plugins/archive/master.zip \
  && unzip master.zip \
  && mkdir -p /usr/share/webapps/rutorrent/plugins \
  && mv plugins-master/* /usr/share/webapps/rutorrent/plugins/
COPY rtorrent.rc /config/rtorrent/
