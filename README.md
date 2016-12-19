# What to do
Install apt-get, Erlang, Elixir, git, ... on Raspbian.

# Usage
## 1. Install Ansible
```sh
brew install ansible
```

## 2. Set ansible hosts
```sh
sudo vim /usr/local/etc/ansible/hosts
```

example...
```sh
[raspi]
192.168.120.164
192.168.120.163
```

## 3. Use playbook
```sh
ansible-playbook playbook.yml -k
```
