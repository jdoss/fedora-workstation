# Fedora Workstation

This is an opinionated playbook to setup a Fedora 32+ workstation with everything you need to start developing on Fedora Linux.

## Quick Setup

Follow these steps to install Ansible, checkout the Fedora Workstation repo, and run the playbook:

```
sudo dnf install ansible -y
git clone https://github.com/jdoss/fedora-workstation.git
cd fedora-workstation
ansible-playbook setup_workstation.yml -e "local_user=yourusername local_user_email=you@example.com" --become -K
```

For further customization, edit `vars/vars.yml` to fit your needs.

## License

The MIT License

Copyright (c) 2020 Joe Doss

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
