# fdk-aac-distrotech-fdk-aac
fdk-aac lib
git clone git://riadhayachi/fdk-aac-distrotech-fdk-aac.git

cd fdk-aac
autoreconf -fiv
./configure --prefix="$HOME/ffmpeg_build" --disable-shared
make
make install
