# hướng dẫn chạy node Cysic 
1. chuẩn bị máy 

    	CPU 1 Core
    	Ram 2 GB
    	Ổ cứng SSD 20 GB
2. đăng kí account
     https://testnet.cysic.xyz/m/referral
3. update
sudo apt-get update && sudo apt-get upgrade -y

sudo apt-get install -y screen curl wget

screen -S cysic

curl -L https://github.com/cysic-labs/phase2_libs/releases/download/v1.0.0/setup_linux.sh > ~/setup_linux.sh && bash ~/setup_linux.sh 0xxx (thay 0xxx = địa chỉ ví của bạn)
5. chạy node

cd ~/cysic-verifier
bash start.sh

nếu cần kết nối lại thì lặp lại bước 5:
  (cd ~/cysic-verifier && bash start.sh).
  xong
