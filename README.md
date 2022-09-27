#  Nginx + WP + MySQL 在 CentOS 8 上

## 建議需求

- RAM : >= 4G
- CPU : >= 2
- Disk : >= 40G
- OS : CentOS 8 or RHEL 8

## 套件需求

- git
- python3-devel
- Ansible

```
  sudo dnf install -y git python3-devel && \
  sudo python3 -m pip install --upgrade pip && \
  sudo pip3 install ansible
```


## 使用方式

請使用 root 角色執行

```
git clone  https://github.com/JeffWen0105/Nginx-WP-MySQL-Ansible-RHEL8.git && \
 cd Nginx-WP-MySQL-Ansible-RHEL8 && ansible-playbook playbook.yml
```


