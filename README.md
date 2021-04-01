# Creating-a-new-user-with-auto-genrated-password-with-Ansible
The purpose of the role in this answer is to generate random password for new_user_name and expire the password immediately. 
The new_user_name is required to change the password on his/her first logon.

When you want to create a new user:

ansible-playbook -i hosts create_user.yml --extra-vars "new_user_name=DevangRadadiya"

