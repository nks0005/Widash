# need modules for install

apt-get update && apt-get install -y nodejs npm make bash build-essential autoconf automake


# make

autoreconf -i
./configure
make