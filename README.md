# kubernetes-may-2021

### Installing minikube
```
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-darwin-amd64
sudo install minikube-darwin-amd64 /usr/local/bin/minikube
```

For detailed instruction, refer the below official page
```
https://minikube.sigs.k8s.io/docs/start/
```

### Make sure minikube is in path
As regular user, type the below command
```
which minikube
```

In case, minikube is already in path, you will get the below out
```
/usr/local/bin/minikue
```

In case, you are not getting the above output then make sure you type the below user normal user(non-root)
Edit the /home/user/.bashrc and append the below line at the end of the file
```
export PATH=/usr/local/bin:$PATH
```

In order to apply the recently added path settings, you need to run
```
source /home/user/.bashrc
```
