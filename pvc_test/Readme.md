
kubectl exec hello-app-cfdd79649-qrbr9  -- sh -c 'echo "Hello World!" > /usr/share/hello/hello.txt'

kubectl exec hello-app-cfdd79649-qrbr9 -- sh -c 'cat /usr/share/hello/hello.txt'



