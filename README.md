
**Script**

Complete installation incouded pre-requirments
```
sudo apt install curl -y  && bash <(curl -s https://raw.githubusercontent.com/saeideros/UDP2RAW_FEC/main/go.sh)
```

Install only script

  
```
rm udpfec.go
sudo apt install wget -y && wget -O /etc/logo.sh https://raw.githubusercontent.com/saeideros/UDP2RAW_FEC/main/logo.sh && chmod +x /etc/logo.sh && wget https://raw.githubusercontent.com/saeideros/UDP2RAW_FEC/main/udpfec.go && go run udpfec.go
```
