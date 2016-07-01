# Facebook IPs
List of IPs corresponding to facebook, this i used to block access to FB site using ALIAS and RULES of PfSense.
Update regulary the file with this:
```
for ip in `whois -h whois.radb.net '!gAS32934' | grep /`; do echo $ip; done ; >> facebookip.txt
```
