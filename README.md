# demo-project
first I launch 4 EC2 instances on Aws 
1-Developer
2-Jenkins
3-Ansible
4-Web-server

1st step is from developer developer machine we create a index.html file and go to github and create a repository then we push it to github repository.We create a password less ssh to connect jenkins to ansible and then ansible to web-server. Then go to jenkins machine install the all plugins and create a job which take the index.html file from github test it and then deploy it on ansible machine. After that from ansible machine we deploy it to web-server machine. And if developer changes any code it automatically show to web-server
