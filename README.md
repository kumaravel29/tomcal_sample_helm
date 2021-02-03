# tomcat_sample_helm
This is the helm chart for tomcat application deployed

## Steps
- Clone this repository and we will deploy the jenkins to a EKS cluster
- Then run the helm command to install the chart
```helm install tomcat -n default -f values.yaml .```
- To expose the Jenkins application on internet via EKS, we select the Loadbalancer service. Then the ELB DNS can be used to access.