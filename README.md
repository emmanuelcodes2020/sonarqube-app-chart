# sonarqube-app-chart

This Helm chart deploys the SonarQube application on a EKS Cluster

Prerequisites:
1) EKS Cluster (AWS) : must be set up first 
2) Helm must be created with the "helm create repo"



## Installing the Chart

To install the chart with the release name : sonarqube-app-release

```

helm install sonarqube-app-release  ./sonarqube-app-chart

```


## Upgrading your Chart

To upgrade the chart with the release name : sonarqube-app-release

```

helm upgrade sonarqube-app-release  ./sonarqube-app-chart

```

## Installing the Chart with values.yaml

To install the chart with the release name : sonarqube-app-release 

```

helm install sonarqube-app-release ./sonarqube-app-chart   --Values ./sonarqube-app-chart/values.yaml

```



## Uninstalling the Chart

To uninstall the sonarqube-app-release deployment:

```

helm uninstall sonarqube-app-release   ./sonarqube-app-chart

```

