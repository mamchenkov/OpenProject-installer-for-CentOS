OpenProject-installer-for-CentOS
================================

Shell script, automating the installation of the OpenProject on to the CentOS box.

This is pretty much a concatenated list of commands from this page:
https://www.openproject.org/projects/openproject/wiki/Installation_on_Centos_65_x64_with_Apache_and_PostgreSQL_93

The order is not exactly the same, because I wanted to make the
process a bit faster.  For example, running yum is heavy, so I try to
run it fewer times.

The only difference is that it is MySQL powered, and not PostgreSQL.
That idea I got from here:
http://possiblelossofprecision.net/?p=1692

