# livepeerbuild

sudo apt-get update
sudo apt-get install build-essential 
sudo apt-get install pkg-config
sudo apt-get install autoconf
sudo apt-get install gnutls-dev
sudo apt-get install git
sudo apt-get install curl
mkdir livepeer && cd livepeer
git clone https://github.com/livepeer/go-livepeer.git
cd go-livepeer
./install_ffmpeg.sh 
ls /home/ubuntu/compiled/lib/pkgconfig | grep gnutls
