# Installing panel x-ui and marzban

### با استفاده از اسکریپت همه کاره 1 و 2 میتوانیم تمام مراحل نصب این دو پنل را به سادگی پیش ببریم

###  Script Number 1 - اسکریپت همه کاره شماره 1 

 ```
curl -Ls https://raw.githubusercontent.com/Mmdd93/v2ray-assistance/refs/heads/main/node.sh -o node.sh sudo bash node.sh
 ```
***
### Script Number 2 - اسکریپت همه کاره شماره 2 

 ```
 bash <(curl -Ls https://raw.githubusercontent.com/dev-ir/assistant-vps/master/install.sh)
 ```
***
### Marzban Node - مرزبان نود 
 ```
curl -sLO https://raw.githubusercontent.com/ItsAML/MarzbanEZNode/main/run.sh && chmod +x run.sh && ./run.sh
 ```
### Marzban ENV - مدریت اسکریپت مرزبان 
 ```
nano /opt/marzban/.env
 ```
### Marzban xray ERRORE - رفع ارور مرزبان ایکسری 
 ```
sudo chmod +x /var/lib/marzban/xray-core/xray
 ```
***

### Fastly Web site - سایت فستلی 
 ```
https://fastly.com/ 
```
### Fake maile web site - سایت ایمیل فیک 
 ```
https://temp-mail.org/fa/
 ```
### Script Fastly cdn - اسکریپت فعالسازی فستلی 

 ```
if (req.http.Upgrade) {
  return (upgrade);
}
 ```
