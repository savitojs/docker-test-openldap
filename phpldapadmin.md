# Access using PhpLDAPAdmin

You can use the following command to view it using PhpLDAPAdmin

```bash
podman run -d --rm -p 6443:443 --env PHPLDAPADMIN_LDAP_HOSTS="#PYTHON2BASH:[{'192.168.122.1': [{'server': [{'tls': False}, {'port': 10389}]},{'login': [{'bind_id': 'cn=admin,dc=sav,dc=com'},{'bind_pass': 'GoodNewsEveryone'}]}]}]" osixia/phpldapadmin:0.9.0
```
