# puppetmaster-bootstrap

Bootstrap Puppetmaster on Ubuntu with Stored Configuration and PostgreSQL.

Only tested on Ubuntu 12.04 LTS.

## Bootstrap puppet master

Run as root

    curl -o puppetmaster-bootstrap -s https://github.com/pkhamre/puppetmaster-bootstrap/raw/master/puppetmaster-bootstrap
    chmod +x puppetmaster-bootstrap
    ./puppetmaster-bootstrap

## Bootstrap puppet agent

Run as root

    curl -o puppet-bootstrap -s https://github.com/pkhamre/puppetmaster-bootstrap/raw/master/puppet-bootstrap
    chmod +x puppet-bootstrap
    ./puppet-bootstrap

## Todo

* Bootstrap a git(olite?) environment for modules
