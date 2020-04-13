
# An Automation Project with Ansible

> A modern sercure architecture.

> Two web Servers, Load Balancer, and a domain name resolution server.

> Keywords: HaProxy, Bind, Apache, Ansible, Playbook, Jinja2, Centos.

## Getting started

> To get started...

### Step 1

- **Setting up the environement**
    - 5 'Centos7' Vms : Ansible Server, 2 Web Servers, 1 DNS Server, 1 Load Balancer.

- **Setting the Ansible VM**

> Ensure that the CentOS 7 EPEL repository is installed, and install Ansible.

```shell
$ yum install epel-release
$ yum install ansible
```

> Configuring Ansible Hosts

```shell
$ vi /etc/ansible/hosts
```
- **[Web]** 🔨
-alias ansible_ssh_host=your_web1server_ip
-alias ansible_ssh_host=your_web2server_ip
- **[Dns]** 🔨
-alias ansible_ssh_host=your_Dnsserver_ip
- **[HaProxy]** 🔨
-alias ansible_ssh_host=your_HaProxyserver_ip

### Step 2

- **HACK AWAY!** 🔨🔨🔨

### Step 3

- 🔃 Create a new pull request using <a href="https://github.com/joanaz/HireDot2/compare/" target="_blank">`https://github.com/joanaz/HireDot2/compare/`</a>.

---

## Project steps

## Configuration

