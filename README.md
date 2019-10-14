

```bash
kubectl create namespace nginx-stdout
kubectl create -f https://raw.githubusercontent.com/goclis/kubernetes-mock-log/master/pod_nginx_stdout.yaml
kubectl create namespace nginx-file
kubectl create -f https://raw.githubusercontent.com/goclis/kubernetes-mock-log/master/pod_nginx_file.yaml
```