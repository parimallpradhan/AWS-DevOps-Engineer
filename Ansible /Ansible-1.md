
Ansible is a congiguration management tool.

/etc/ansible/ansible.cfg 
ansible.cfg will store all configuration details.
Ansible Master commands
1  clear
    2  yum install epel-release
    3  clear
    4  amazon-linux-extras install epel
    5  yum install ansible -y
    6  ansible --version
    7  clear
    8  history
    9  clear
   10  ssh-keygen
   11  ls
   12  cd /root/.ssh/
   13  ls
   14  cat id_rsa.pub
   15  vi authorized_keys
   16  cat authorized_keys
   17  clear
   18  cat id_rsa.pub
   19  ssh 54.166.255.171
   20  history

    Ansible node commands
    ssh-keygen
    2  cd /root/.ssh/
    3  l
    4  ls
    5  cat id_rsa.pub
    6  vi authorized_keys
    7  history

Playbook : Where it is going to perform task.
/etc/ansible/hosts : It will store the target machine ips.




    
