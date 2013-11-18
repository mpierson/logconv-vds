logconv-vds
===========

LDAP log analysis tool for Dell Quick Connect Virtual Directory Server

This perl script is a version of the open source 'logconv.pl', modified to accomodate the access log format of Dell QC-VDS.

Dell Quick Connect Virtual Directory Server: http://www.quest.com/quest-one-quick-connect-virtual-directory-server/

Original logconv.pl script: https://git.fedorahosted.org/cgit/389/ds.git/plain/ldap/admin/src/logconv.pl

The VDS access log differs from the standard OpenLDAP access log in (at least) the following ways:
 - minor change to date format
 - quotes around some fields
 - file descriptor information not logged
 - connection open/close events not logged
