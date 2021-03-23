mac-ansible
===========

I use this project to configure my macOS the way I like it. That way I can wipe
and re-install with less effort. See my
[blog post](https://adamj.eu/tech/2019/03/20/how-i-provision-my-macbook-with-ansible/).


Getting Started (How to Install Ansible)
----------------------------------------

1. Install [homebrew](http://brew.sh/) with the command from the site
2. `brew install pyenv`
3. `pyenv install <latest_python_version>` (Check playbook up to date)
4. Make sure pyenv's python on path (it will be after my shell settings are in place from playbook)
   https://realpython.com/intro-to-pyenv/    (genau nach Anleitung installieren)
5. `python -m venv venv`
6. `source venv/bin/activate`
6. `pip install --upgrade pip`  (if you get an error to install Ansible)
5. `pip install ansible` (always the best way to install Ansible)
6. Then `./playbook.yml`
7. Chrome manuell installieren https://www.google.com/chrome/
8. Lastpass Plubins manual silet install https://lastpass.com/company/#!/settings/install-software


Use Ansible with a remote Mac you have to enable ssh
----------------------------------------------------
1. (On the Mac you want to connect to:) Go to System Preferences > Sharing.
2. Enable 'Remote Login'.

```
You can also enable remote login on the command line:
sudo systemsetup -setremotelogin on
```

Fork! Copy! Adapt!
------------------

This is distributed under the Unlicense so you can do whatever you want with
it, see LICENSE.
