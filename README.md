# fdk-aac-distrotech-fdk-aac

clone the repository

git clone https://github.com/riadhayachi/fdk-aac-distrotech-fdk-aac.git

cd fdk-aac
autoreconf -fiv
./configure --prefix="$HOME/ffmpeg_build" --disable-shared
make
make install
