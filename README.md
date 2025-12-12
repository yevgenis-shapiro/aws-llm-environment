<img width="1246" height="600" alt="image" src="https://github.com/user-attachments/assets/6e1bf1c7-5f33-4635-b26a-4de466314049" />


## AWS | LLM Environment 🚀🚀🚀
This typically refers to running Kubernetes worker and master nodes as Docker containers, instead of as real VMs or machines.
This model is used mostly in local development and demo setup 🐳


🎯  Architecture
```
✅ Source Control (GitLab)
✅ Infrastructure Orchestration Layer (Terraform Core)
✅ Cloud Execution Layer → (AWS EC2)
✅ Kubernetes Orchestration Layer (kind Cluster)
✅ AI/ML Runtime Layer (LLM + Vector DB Stack)
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

