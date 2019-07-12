hmpps-delius-core-umt-bootstrap
=========

Bootstrap Ansible role to setup the delius-core User Management Tool (UMT).


Role Variables
--------------

```yaml
region:             AWS Region
environment_name:   Environment eg. delius-core-dev
project_name:       Project eg. delius-core
database_url:       JDBC URL to connect to the Delius database
database_username:  Database username
database_password:  Database password 
ldap_url:           LDAP URL eg. ldap://example.com:389
ldap_bind_username: LDAP admin username
ldap_bind_password: LDAP admin password
ldap_user_base:     Base root for users eg. ou=Users,dc=example,dc=com
ndelius_log_level:  Log level (default=INFO)
jwt_secret:         Security key used for encrypting JWT session tokens (default=random string)
delius_secret:      Shared secret between Delius and UMT for delegated authentication (default=random string)
config_location:    Path to the UMT config file eg. /app/config
```

License
-------

MIT

Author Information
------------------

HMPPS Digital Studio
