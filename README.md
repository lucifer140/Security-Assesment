# Security-Assesment
**Kube-Bench**

kube-bench is a tool that checks whether Kubernetes is deployed securely by running the checks documented in the CIS kubernetes Benchmark.

Getting started with kube-bench
```
git clone https://github.com/aquasecurity/kube-bench.git
cd kube-bench
```
Install the Drupal
```
helm repo add my-repo https://charts.bitnami.com/bitnami
helm install my-release my-repo/drupal -n namespace
```
View your kubernetes objects
```
kubectl get all -n namespace
```
Scans at pod level
```
kubectl apply -f job.yaml
```
Get your logs
```
kubectl logs pod/job_name -n namespace_name
```


**Kube-Hunter**

kube-hunter hunts for security weaknesses in Kubernetes clusters that runs under an Apache 2.0 license.
Getting started with kube-hunter
```
git clone https://github.com/aquasecurity/kube-hunter.git
cd kube-hunter
```
Install the Wordpress
```
helm repo add my-repo https://charts.bitnami.com/bitnami
helm install wp-test bitnami/wordpress -n namespace
```
View your kubernetes objects
```
kubectl get all -n namespace
```
Scans at pod level
```
kubectl apply -f job.yaml
```
Get your logs
```
kubectl logs pod/job_name -n namespace_name
```
