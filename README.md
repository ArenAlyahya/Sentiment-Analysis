# Sentiment-Analysis


The steps to get the application to work on Google Kubernetes Engine:
- The following will lunsh the website:  http://34.136.143.173/ 

Docker images: 
- https://hub.docker.com/repository/docker/arenalyahya/sentiment-analysis-web-app2 
- https://hub.docker.com/repository/docker/arenalyahya/sentiment-analysis-logic2 
- https://hub.docker.com/repository/docker/arenalyahya/sentiment-analysis-frontend2 


Overall:
  The front-end app is opening successfully, but some of the exposing configuration is not fully successful even though several methods was tested, such as creating a service for the analysis-logic2 deployment using different service types:  Cluster IP, Node IP, or Load balancers. Moreover, I tried use Ingress to connect the services together and mimic the YAMIL files oin GitHub repository: https://github.com/rinormaloku/k8s-mastery . 
