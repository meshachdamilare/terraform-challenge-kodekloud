### Challenge 1

In this challenge we will deploy several Kubernetes resources using terraform.
- Configure terraform and provider settings within provider. file. This also update the kubeconfig file for the cluster.
- Create a terraform resource frontend for kubernetes deployment
- Create a terraform resource frontend-service for kubernetes service
- Deploy
    ```
    terraform init
    terraform plan
    terraform apply
    ```