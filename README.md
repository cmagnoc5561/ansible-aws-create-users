# aws
Make sure your cli-aws is working properly in your terminal.
Install Ansible with the command <b>apt-get install ansible</b>.<br>
Install Boto from pip3 install boto.<br>
Install the read_csv and teh aws.iam collection for ansible by typing:<br>
  ansible-galaxy collection install community.general<br>
  ansible-galaxy collection install community.aws<br>
  
Create your groups first so you can allocate users to the respective groups and its policies.<br>

To delete users, change the term 'present' to 'absent' in the state line.<br>
