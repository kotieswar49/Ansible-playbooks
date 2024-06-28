1.sudo apt update

2.ssh-keygen

3.cat id_ed25519.pub 

4.vim ansible.sh

5../ ansible.sh 

6.chmod 744 ansible.sh 

7.ansible --version

8.cd /etc/ansible/

9.ls

10.vim hosts 

11.sudo vim hosts

12.ansible -m ping all

13.sudo vim play1.yml

14.ansible-playbook play1.yml --syntax-check

15.ansible-playbook play1.yml --check
