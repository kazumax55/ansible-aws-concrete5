ansible-aws-concrete5
====
EC2(amazon linux)でconcrete5に必要なPHP設定とApache設定を行うAnsible Playbookです。
# How To Setup

## System Requirement

* OS:Amazon Linux
* ansible

## How to Install a localhost

```
sudo yum install - ansible
sudo su - ec2-user
git clone https://github.com/kazumax55/ansible-aws-concrete5.git
cd ansible-aws-concrete5
ansible-playbook -i hosts site.yml
```
## 設定
必要に応じて以下のファイルを修正してください。

#### Apache設定

Apacheのdomain設定 -> roles/apache/vars/main.yml
