# Installing panel x-ui and marzban

***

### اسکریپت همه کاره شماره 1
 ```
curl -Ls https://raw.githubusercontent.com/Mmdd93/v2ray-assistance/refs/heads/main/node.sh -o node.sh
sudo bash node.sh
 ```
***
### اسکریپت همه کاره شماره 2

 ```
 bash <(curl -Ls https://raw.githubusercontent.com/dev-ir/assistant-vps/master/install.sh)
 ```
***
### مرزبان نود 
 ```
sudo bash -c "$(curl -sL https://github.com/Gozargah/Marzban-scripts/raw/master/marzban-node.sh)" @ install
 ```
### اسکریپت مدیریت مرزبان 
 ```
nano /opt/marzban/.env
 ```
### رفع خطاهای هسته ایکسری مرزبان 
 ```
sudo chmod +x /var/lib/marzban/xray-core/xray
 ```
***
### آموزش سایت فستلی 
***
### سایت فستلی 
 ```
https://fastly.com/ 
```
### سایت ایمیل فیک 
 ```
https://temp-mail.org/fa/
 ```
### اسکریپت شرط فستلی

 ```
if (req.http.Upgrade) {
  return (upgrade);
}
 ```
