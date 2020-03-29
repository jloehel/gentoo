Simply add the file /etc/portage/repos.conf/jloehel.conf::

    [jloehel]
    location = /usr/local/portage/jloehel
    sync-type = git
    sync-uri = https://github.com/jloehel/gentoo.git
    auto-sync = yes

and run emerge --sync jloehel
