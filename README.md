[![Build Status](https://travis-ci.org/wtanaka/ansible-role-alex.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-alex)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-alex.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-alex)

wtanaka.alex
=============

Installs alex

Alex is a tool for generating lexical analysers in Haskell. It takes a
description of tokens based on regular expressions and generates a
Haskell module containing code for scanning text efficiently. It is
similar to the tool lex or flex for C/C++.

Example Playbook
----------------

    - hosts: servers
      roles:
         - wtanaka.alex

License
-------

GPLv2

Author Information
------------------

http://wtanaka.com/
