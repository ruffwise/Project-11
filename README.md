# Project-11 AUTOMATE PROJECT 7 TO 10

### Install Ansible

`sudo apt install ansible -y`
![](/images/ansible-version.png)

### configure jenkins build job to save repository content each time a change is made

![](/images/Project-ansible.png)

### create common playbook

![](/images/inventory.png)

![](/images/playbook.png)

### Run first ansible test to install wireshark

`ansible-playbook -i /var/lib/jenkins/jobs/Ansible/builds/5/archive/inventory/dev.yml /var/lib/jenkins/jobs/Ansible/builds/5/archive/playbooks/common.yml`

![](/images/ansible-test.png)

### Run 2nd ansible test to create directory with a file

![](/images/ansible-create-file.png)

![](/images/ansible-create-file2.png)
