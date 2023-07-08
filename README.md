
# How To Setting Adguard Home

## AdGuHo-NoteSettings 
Download: https://github.com/AdguardTeam/AdGuardHome/releases

## Add set Bootstrap DNS servers
Bootstrap DNS servers are used to resolve IP addresses of the DoH/DoT resolvers you specify as upstreams.
- Biznet:
```
203.142.82.222
203.142.84.222
```
- Indihome:
```
202.134.0.62
222.124.18.62
```

# Add set Upstream DNS servers
```
https://dns10.quad9.net/dns-query
https://dns.adguard-dns.com/dns-query
https://doh.opendns.com/dns-query
https://dns.google/dns-query
https://doh.tiar.app/dns-query
```

# Add set filter DNS blocklists
- AdRules: https://raw.githubusercontent.com/Cats-Team/AdRules/main/adblock_plus.txt
- NeoDevHost: https://raw.githubusercontent.com/neodevpro/neodevhost/master/adblocker
