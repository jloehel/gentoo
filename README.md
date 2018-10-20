Simply add the file /etc/portage/repos.conf/phreeek.conf::

    [phreeek]
    location = /usr/local/portage/phreeek
    sync-type = git
    sync-uri = https://github.com/phreeek/gentoo.git
    auto-sync = yes

and run emerge --sync phreeek
