## Zimbra Letsencrypt SSL Renew
Automate the deploy of letsencrypt certificates on Zimbra.

**Based on Zimbra Article  KB 22434** : https://wiki.zimbra.com/wiki/Installing_a_LetsEncrypt_SSL_Certificate

## Let's Begin
```sh
git clone https://github.com/paulo-amaral/Easy-Letsencrypt-Zimbra.git
```
## Set permission
```
chmod +x renew_certificate.sh 
```

## Run
```
sh renew_certificate.sh
```

## Set crontab
This script automatic setup a crontab/cron job to schedule the renew of certificate.

