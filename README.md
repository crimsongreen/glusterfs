### Overview:
This is an ansible playbook for deploying GlusterFS on two CentOS 7 servers.

### Prerequisites:
2x CentOS 7 servers
1x staging server or PC running Ansible 1.9.2 

### Deployment:
Edit your local /etc/hosts file and add your 2 CentOS server IPs and hostnames.

```
192.168.0.1 glusterfs-1
192.168.0.2 glusterfs-2
```

You're now ready to run the playbook!

```
ansible-playbook -i hosts site.yml 
```
