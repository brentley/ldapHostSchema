ldapHostSchema
==============

Dictate who is allowed access to which hosts and store in LDAP

This is checked if /etc/pam_ldap.conf contains:
pam_check_host_attr yes

I typically keep /etc/pam_ldap.conf symlinked to /etc/ldap.conf.

I *think* I adapted this from the account schema.
