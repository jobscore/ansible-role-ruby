[![Build Status](https://travis-ci.org/jobscore/ansible-role-ruby.svg?branch=master)](https://travis-ci.org/jobscore/ansible-role-ruby)

Ruby
=========

Install Ruby from the source in a Ubuntu box

Requirements
------------

None

Role Variables
--------------

`ruby_version: 3.2.2`
It defines the ruby version to install

`disable_gem_docs: true`
Skip docs while downloading gems

For further reference check out [defaults/main.yml](/defaults/main.yml)

Dependencies
------------

None

Example Playbook
----------------

```
    - hosts: all
      roles:
         - role: jobscore.ruby
           ruby_version: 3.2.2
```

License
-------

GPL V3

Author Information
------------------

This role was created by [Eric Magalhães](https://emagalha.es) while working for [JobScore Inc](https://jobscore.com).
