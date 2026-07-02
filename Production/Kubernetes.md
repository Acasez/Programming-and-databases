Kubernetes is a program to direct multiple [[Container|containers]] and test different environments at once. Kubernetes is complex, but useful if you developing and want to quickly test software for many types of machines. 

### Pod
The smallest unit in Kubernetes. Contains one or more containers that run together and share network and storage space. Web apps tend to have one container per pod.
### Node
A computer, physical or virtual, that run pods. Kubernetes places pods by nodes automatically based on resources and defined rules.
### Deployment
Describes how copies of your app to run and makes sure they keep running.
### Service
Provides a stable network name and entry for your pods, even when they are added or change IP.
