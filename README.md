# Installation

You'll need to have the Helm repository added to your local environment:

``` bash
helm repo add regiocloud https://regiocloud.github.io/helm-charts
helm repo update
```
Which should allow you to see the Hookshot chart in the repo:

``` bash
helm search repo regiocloud

NAME                          	CHART VERSION	APP VERSION	DESCRIPTION                                       
regiocloud/alertmanager-matrix	1.0.0        	v0.7.2     	A bot to receive Prometheus Alertmanager webhoo...
regiocloud/calcom             	0.5.1        	v3.7.8     	A Helm chart for calcom                           
regiocloud/hookshot           	0.2.0        	5.3.0      	Deploy a Matrix Hookshot instance to Kubernetes   
regiocloud/lemonldap-ng       	0.1.0        	2.16.2     	A Helm chart for lemonLDAPng                      
regiocloud/shlink-backend     	2.12.5       	3.6.4      	A PHP-based self-hosted URL shortener that can ...
```
