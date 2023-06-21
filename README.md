## SonarQube Documentation
### Create namespace sonarqube in cluster
Deploy postgres (if postgres is already deployed then just add username ,password  and url in sonarqube config<br>
Deploy sonarqube in cluster.Clone code (https://github.com/Rabindra20/sonarqube_k8s.git)<br>
Kubectl apply -f . -n sonarqube<br>
port forward<br>
Login sonarqube dashboard<br>
Add project and generate token in ui<br>
Copy the configuration file and paste in local<br>
Start sonarqube scanner <br>
## For new quality profile
Create new quality profile and add rules<br>
For github Action <br>
Add configuration in workflow and add env secrets (like sonar_token and sonar_host_url)<br>
## For custom rule
Goto rules<br>
Click on template and create new rule<br>

https://docs.sonarqube.org/latest/extend/adding-coding-rules/<br>
For checking project <br>
