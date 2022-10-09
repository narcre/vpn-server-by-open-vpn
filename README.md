# setup vpn server by openvpn in ubuntu


```
apt update 
```

``` 
apt upgrade
```

``` 
dig +short myip.opendns.com @resolver1.opendns.com
```

```
wget https://git.io/vpn -O openvpn-install.sh
```

``` 
chmod +x openvpn-install.sh
```

``` 
sudo ./openvpn-install.sh 
```

``` 
systemctl status openvpn-server@server.service
```


* https://openvpn.net/client-connect-vpn-for-windows/

