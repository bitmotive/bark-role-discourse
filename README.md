BARK: DISCOURSE
=========

Install & Configure Discourse with Sane Defaults.

Requirements
------------

All roles in the Bitmotive Ansible Role Kit are configuration driven.

Customize this role by providing environment variables in either your
shell environment, host specific in group_vars/, or at the CLI when
prompted at runtime. 

Role Variables
--------------

**DISCOURSE_HOSTNAME**:

The hostname for Discourse installation.

**DISCOURSE_EMAIL**:

The e-mail that will be used to send discourse transactional messages.

**DISCOURSE_SMTP_ADDRESS**

The SMTP address for the Discourse mail service.

**DISCOURSE_SMTP_PORT**

The SMTP port for the Discourse mail service.

**DISCOURSE_SMTP_USER**

The SMTP user for the Discourse mail service.

**DISCOURSE_SMTP_PASSWORD**

The Discourse SMTP password.

**DISCOURSE_MEMORY**

The memory that Discourse should use on the machine, measured in MB.

**DISCOURSE_CORES**

The number of server CPU cores that Discourse should use.

**DISCOURSE_PORT**

The server port on which Discourse should bind.

**DISCOURSE_NGINX_CONFIG_NAME**

The name you would like to assign to the NGINX config when copied to target.

**DISCOURSE_NGINX_SSL_CERTIFICATE**

The location of the SSL certificate public key for Discourse.

**DISCOURSE_NGINX_SSL_CERTIFICATE_KEY**

The location of the SSL certificate private key for Discourse.


Dependencies
------------

Only tested with MailGun via SMTP, however, it should work with any other
SMTP service for transactional email.

License
-------

MIT

Author Information
------------------

A Bitmotive Project: Build. Incubate. Train.
https://bitmotive.com 
