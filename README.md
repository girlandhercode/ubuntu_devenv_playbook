Ubuntu DevEnv Setup Playbook
=========

From fresh Ubuntu-flavored install or fresh WSL to functioning development environment.

Requirements
------------

Before this role can be ran on `localhost`, the following must be installed manually:

- python 2
  ` $ sudo apt-get update && sudo apt-get install python-minimal`
- pip
  ` $ sudo apt-get update && sudo apt-get install python-pip`

Alternitive `pip` installation:
```{bash}


# Installing using apt-get installs a system wide pip, not just a local
# one for your user. Try this command to get pip running as system ...


  $ sudo apt-get install python-pip python-dev build-essential


# Then pip will be installed without no issues and you will be ale to
# use "sudo pip...".
```

Role Variables
--------------

A description of the settable variables for this role in `defaults/main.yml`



Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

MIT License

Copyright (c) 2018  Girlandhercode [CNM]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Author Information
------------------

Crafted by Girlandhercode with <3
