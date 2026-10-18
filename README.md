Plesk için ücretsiz openlitespeed kurulumu
cd /tmp
wget -O openlitespeed.zip "https://raw.githubusercontent.com/sesliyazilim40/plesk-openlitespeed/refs/heads/main/openlitespeed-sesliyazilim-plesk.zip"
plesk bin extension --install /tmp/openlitespeed.zip
