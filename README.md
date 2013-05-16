ldap-tools
==========================

scripts/config files to ease ldap server tasks

ldif2csv
-----------
  This is a simple python script to convert an ldif file to csv
  it supports command line atttribute lists

Usage
<pre>
ldif2csv [options]

Options:
  -h, --help            show this help message and exit
  -o CSV_FILE, --csv=CSV_FILE
                        csv input file
  -i LDIF_FILE, --ldif=LDIF_FILE
                        ldif file to write to
  -a LDIF_ATTR, --attr=LDIF_ATTR
                        attribute
</pre>

Sample usage 

<pre>
ldif2csv -i ~/Downloads/users.ldif -o ~/Downloads/users.csv -a name -a mail -a title -a manager
</pre>


