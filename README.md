nmap : nmap -p 1-65535 -T4 -A -v IP_ADDR_CENTOS


NGROK:
wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz --no-check-
certificate
tar -xzf ngrok-v3-stable-linux-amd64.tgz -C /usr/local/bin
ngrok authtoken YOUR_AUTH_TOKEN
ngrok tcp 22
