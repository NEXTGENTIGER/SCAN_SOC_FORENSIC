python3 forensic_analyzer.py .....chemin.....malware_test.exe --verbose


-------------------------------------------------------------------------
sudo apt install zaproxy

zaproxy -daemon -port 8080 -config api.addrs.addr.name=.* -config api.addrs.addr.regex=true -config api.key=changeme

python3 zap_scan.py https://supdevinci.fr/
------------------------------------------------------
apt install python3-nmap

python nmap_scan.py 192.168.1.15  
