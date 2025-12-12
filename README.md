<img width="1246" height="600" alt="image" src="https://github.com/user-attachments/assets/834a55d0-fc94-40f3-92e5-4515d962bc86" />


## AWS LLM Environment | Kind 🚀🚀🚀
Kind (Kubernetes IN Docker) is an open-source tool that allows you to run local Kubernetes clusters where each node is a Docker container.


🎯  Key Features
```
✅ Deploy Infrastructure
✅ Launch EC2 Instance
✅ Install Dependencies 
✅ Prepare Kubernetes 
✅ Cluster Post-Configuration
```

🚀 
```
terraform init
terraform validate
terraform plan -var-file="template.tfvars"
terraform apply -var-file="template.tfvars" -auto-approve
```

🧩 Config 

```
scp -i ~/.ssh/<your pem file> <your pem file> ec2-user@<terraform instance public ip>:/home/ec2-user
chmod 400 <your pem file>
```

