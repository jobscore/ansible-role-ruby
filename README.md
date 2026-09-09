[![CI](https://github.com/jobscore/ansible-role-ruby/actions/workflows/ci.yml/badge.svg)](https://github.com/jobscore/ansible-role-ruby/actions/workflows/ci.yml)

Ruby
=========

Install Ruby from the source in a Ubuntu box

Requirements
------------

None

Role Variables
--------------

`ruby_version: 4.0.6`
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
           ruby_version: 4.0.6
```

License
-------

GPL V3

Author Information
------------------

This role was created by [Eric Magalhães](https://github.com/ericovis) and [Glauber Batista](https://github.com/GlauberrBatista) while working for [JobScore Inc](https://jobscore.com).
