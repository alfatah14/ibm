nmap : nmap -p 1-65535 -T4 -A -v IP_ADDR_CENTOS


NGROK:
1. wget https://bin.equinox.io/c/bNyj1mQVY4c/ngrok-v3-stable-linux-amd64.tgz --no-check-
certificate
2. tar -xzf ngrok-v3-stable-linux-amd64.tgz -C /usr/local/bin
3. ngrok authtoken 2hifptZinPB84D7nEp654FfGvmo_6c2qEcNoTae5984pKBnBo
4. ngrok tcp 22
