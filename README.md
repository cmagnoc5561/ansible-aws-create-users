# aws

Make sure your *cli-aws* is working properly in your terminal.<br>
Install Ansible with the command `apt-get install ansible`</i>.<br>
Install Boto with <i>`pip3 install boto`</i>.<br>
Install the read_csv and teh aws.iam collection for ansible by typing:<br>
`ansible-galaxy collection install community.general`<br>
`ansible-galaxy collection install community.aws`<br>

Create your groups first so you can allocate users to the respective groups and its policies.<br>

To delete users, change the term 'present' to 'absent' in the state line.<br>
