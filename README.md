# Fix: Broken emojis

Install the symbola fontpack and you'll be good to go.

~~~bash
FONTHOME=~/.local/share/fonts/
mkdir -p $FONTHOME/inconsolata
cd $FONTHOME/inconsolata
wget 'https://github.com/google/fonts/blob/master/ofl/inconsolata/Inconsolata%5Bwdth%2Cwght%5D.ttf'
fc-cache -fv
~~~
