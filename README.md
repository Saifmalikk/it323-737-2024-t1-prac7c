# it323-737-2024-t1-prac7c

To access the deployed application using the command prompt, you'll need to run the `kubectl port-forward` command. Open your command prompt or terminal, navigate to the directory where your Kubernetes configuration files are located, and execute the command `kubectl port-forward my-python-app-deployment-5d8c7448c6-drh6q 8080:80`. This command forwards traffic from your local port 8080 to port 80 on the specified Kubernetes pod. Once the port forwarding is set up, you can access your application by opening a web browser and navigating to `http://localhost:8080`.
