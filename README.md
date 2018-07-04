2 Build dockerfile

 git clone https://github.com/devops-ukr/k8s.git .
      
 docker build -t k8s:v1 .
     
 docker run --name k8s -itd k8s:v1 /bin/bash
How to use

To connect to container, run the command

 docker attach k8s
