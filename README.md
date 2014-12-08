# Simple Public Key Infrastructure

# Usage

~~~ bash
# create a new root CA and signing CA
$ ./simple-pki init

# create a SSL/TLS server certificate
$ ./simple-pki create-server subdomain.mydomain.com

# create a S/MIME email certificate
$ ./simple-pki create-email user@mydomain.com
~~~

# References

* [http://pki-tutorial.readthedocs.org/en/latest/simple/]()
