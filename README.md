![Easy-Letsencrypt-Zimbra](https://socialify.git.ci/paulo-amaral/Easy-Letsencrypt-Zimbra/image?description=1&font=KoHo&forks=1&issues=1&language=1&owner=1&pattern=Charlie%20Brown&pulls=1&stargazers=1&theme=Dark)


## Zimbra Letsencrypt SSL Renew
Automate the deploy of letsencrypt certificates to Zimbra.

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

