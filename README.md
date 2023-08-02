# CICD Pipeline To Deploy To Kubernetes Cluster Using Jenkins | Jenkins Kubernetes Integration

### Run jenkins container:
`docker run -u 0 --privileged --name jenkins -it -d -p 8080:8080 -p 50000:5000 \`  
`-v /var/run/docker.sock:/var/run/docker.sock \`  
`-v $(which docker):/usr/bin/docker \`  
`-v /ixkat/Cursos/Morioh/CICDPipelineToDeployToKubernetes/jenkins_home:/var/jenkins_home \`  
`jenkins/jenkins:latest`

