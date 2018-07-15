# recon-moloch

```
ansible-playbook playbook.yml
```

```
/data/moloch/db/db.pl http://ESHOST:9200 init
/data/moloch/db/db.pl http://ESHOST:9200 upgrade
/data/moloch/bin/moloch_add_user.sh admin "Admin User" THEPASSWORD --admin
systemctl start molochviewer.service
```
