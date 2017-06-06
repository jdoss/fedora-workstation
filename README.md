# Fedora Workstation

This is an opinionated playbook to setup a Fedora 25+ workstation with everything you need to start developing on Fedora Linux.

## Quick Setup

Make sure Ansible 2.2+ is installed on your workstation and run the following inside the repository:

`ansible-playbook setup_workstation.yml -e "local_user=yourusername local_user_email=you@example.com local_user_passwordless_sudo=true  enable_sshd=true enable_fail2ban=true install_chefdk=true install_chrome=true install_googletalk=true install_slack=true install_spotify=true install_zoom=true install_atom=true --become --ask-sudo-pass`

For further customization, edit `vars/vars.yml` to fit your needs.

## License

The MIT License

Copyright (c) 2017 Joe Doss

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
