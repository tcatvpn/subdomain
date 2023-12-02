pkg update && pkg upgrade -y
pkg install python
pkg install python3
pip install requests loguru multithreading bugscanner
pkg install golang
pkg install vim
git clone https://github.com/tcatvpn/subdomain.git
cd subdomain 
pip install -r requirements.txt
python3 scan.py
