# fail2ban
Skripte, Erweiterungen für Fail2Ban

## filter.d
* ```apache-jndi.conf```: Sperrt Log4j-Attacken
* ```nextcloud.conf```: Sperrt fehlgeschlagene Nextcloud-Logins
* ```ox-python-requests.conf```: Sperrt IPs die Zugriff via `python-request` versuchen
* ```ox-spammail.conf```: Sperrt bei zu vielen POST-Requests über die Open-Xchange-API
* ```seafile-auth.conf```: Sperrt fehlgeschlagene Seafile-Logins

## jail.d
* ```apache-jndi.conf```: Sperrt Log4j-Attacken
* ```nextcloud.conf```: Sperrt fehlgeschlagene Nextcloud-Logins
* ```ox-python-requests.conf```: Sperrt IPs die Zugriff via `python-request` versuchen
* ```ox-spammail.conf```: Sperrt bei zu vielen POST-Requests über die Open-Xchange-API
* ```seafile-auth.conf```: Sperrt fehlgeschlagene Seafile-Logins
