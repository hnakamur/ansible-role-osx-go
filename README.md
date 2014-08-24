osx-go
======

An Ansible role to install go

Requirements
------------

[Homebrew](http://brew.sh/) must be installed.

Role Variables
--------------

- osx_go_gopath: ~/go
    - value for GOPATH environment variable. see [About the go command - The Go Programming Language](http://golang.org/doc/articles/go_command.html) for GOPATH

Dependencies
------------

- hnakamur.oh-my-zsh

Example Playbook
----------------

    - hosts: servers
      roles:
         - hnakamur.osx-go

License
-------

MIT

Author Information
------------------

[Hiroaki Nakamura]( http://hnakamur.github.io/ )
