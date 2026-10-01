# roblox-launcher

cd ~/Downloads
tar xzf roblox-linux-client-m1.tar.gz
cd rlc 

./packaging/build-deb.sh

sudo apt install ./roblox-linux-client_0.1.0_amd64.deb

rlc-client --keep-open

cat ~/.local/state/roblox-linux-client/logs/client.log



sudo apt install ~/Downloads/roblox-linux-client*.deb
