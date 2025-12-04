# node_exporter_ansible_auto_deploy
# STEP 1

Run python_check.yml to check if python and pip are installed on target machines and to install them if they arent preinstalled => ansible-playbook /path/to/python_check.yml

# STEP 2

Run download_docker.yml to install docker on machines that dont have it already => ansible-playbook /path/to/download_docker.yml

# STEP 3

Run deploy_node.yml to deploy node exporter on machines that dont have it alread => ansible-playbook /path/to/deploy_node.yml
