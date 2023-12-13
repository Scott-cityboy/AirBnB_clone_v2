# 0x03. AirBnB clone - Deploy static

Learning Objectives
What is Fabric
How to deploy code to a server easily
What is a tgz archive
How to execute Fabric command locally
How to execute Fabric command remotely
How to transfer files with Fabric
How to manage Nginx configuration
What is the difference between root and alias in a Nginx configuration

Task Descriptions
0-setup_web_static.sh : Write a Bash script that sets up your web servers for the deployment of web_static.
 It must

1-pack_web_static.py : Write a Fabric script that generates a .tgz archive from the contents of the web_static folder of your AirBnB Clone repo, using the function do_pack.

2-do_deploy_web_static.py : Write a Fabric script (based on the file 1-pack_web_static.py) that distributes an archive to your web servers, using the function do_deploy

3-deploy_web_static.py : Write a Fabric script (based on the file 2-do_deploy_web_static.py) that creates and distributes an archive to your web servers, using the function deploy

100-clean_web_static.py : Write a Fabric script (based on the file 3-deploy_web_static.py) that deletes out-of-date archives, using the function do_clean.

101-setup_web_static.pp : Redo the task #0 but by using Puppet.
