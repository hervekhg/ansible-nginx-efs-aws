# ansible-nginx-efs-aws
Ansible script using as AWS user-data script to deploy web serveur with Nginx and EFS mount

# How to use
<code bash>
ansible-playbook -vvv /home/ec2-user/hervekhg/main.yml -e env=\"${env}\" -e install_name=\"${install_name}\" -e project_name=\"${project_name}\" -e version_lot=\"${version_lot}\""
</code>
