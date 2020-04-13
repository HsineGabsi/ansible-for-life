
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
    - alias ansible_ssh_host=your_web1server_ip
    - alias ansible_ssh_host=your_web2server_ip
- **[Dns]** 🔨
    - alias ansible_ssh_host=your_Dnsserver_ip
- **[HaProxy]** 🔨
    - alias ansible_ssh_host=your_HaProxyserver_ip

### Step 2

- **Setting up the Slaves**

> The way you update CentOS and all its packages.
```shell
$ yum update -y
```
> Ensure that the @ matches with the @ in /etc/ansible/hosts.
```shell
$ ip a
```

### Step 3

- 🔃 Clone this repo to your local machine using https://github.com/fvcproductions/SOMEREP

---

## Project steps

## Configuration

