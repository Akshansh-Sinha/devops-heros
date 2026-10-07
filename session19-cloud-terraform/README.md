# Session 19: Cloud & Terraform in Action

This session explores core cloud architecture concepts on Amazon Web Services (AWS) and automates cloud infrastructure provisioning using Terraform.

---

## Key Modules & Topics

1. **Cloud Computing Fundamentals:**
   - **Service Models**: IaaS (Infrastructure as a Service), PaaS, SaaS.
   - **Global Infrastructure**: AWS Regions, Availability Zones (AZs), and edge locations.
   - Related Directories: [`01-cloud-service-models/`](file:///home/akshanshsinha/DevOps/devops-heros/session19-cloud-terraform/01-cloud-service-models), [`02-regions-and-availability-zones/`](file:///home/akshanshsinha/DevOps/devops-heros/session19-cloud-terraform/02-regions-and-availability-zones)

2. **AWS Networking Essentials:**
   - **VPC (Virtual Private Cloud)**: Custom CIDR blocks (e.g. `10.20.0.0/16`).
   - **Subnets**: Public vs private subnets and IP range calculations.
   - **Internet Gateway (IGW)**: Connecting your VPC to the public internet.
   - **Route Tables**: Directing subnet traffic to local routes and Internet Gateways.
   - **Security Groups**: Stateful instance-level firewalls controlling inbound and outbound traffic.
   - Related Directories: [`03-vpc-and-subnets/`](file:///home/akshanshsinha/DevOps/devops-heros/session19-cloud-terraform/03-vpc-and-subnets), [`04-route-tables-and-internet-gateway/`](file:///home/akshanshsinha/DevOps/devops-heros/session19-cloud-terraform/04-route-tables-and-internet-gateway), [`05-security-groups/`](file:///home/akshanshsinha/DevOps/devops-heros/session19-cloud-terraform/05-security-groups)

3. **Terraform Infrastructure as Code (IaC):**
   - Defining AWS provider configurations and region variables.
   - Writing declarative HCL code for VPCs, Subnets, Gateways, and Security Groups.
   - Terraform lifecycle workflow: `init`, `validate`, `plan`, `apply`, `destroy`.
   - Related Directories: [`06-terraform-vpc/`](file:///home/akshanshsinha/DevOps/devops-heros/session19-cloud-terraform/06-terraform-vpc), [`07-terraform-workflow/`](file:///home/akshanshsinha/DevOps/devops-heros/session19-cloud-terraform/07-terraform-workflow)

4. **Hands-on Capstone Mini-Project:**
   - End-to-end automated deployment of an AWS VPC, public subnet, route table, internet gateway, and web security group using Terraform.
   - See [08-mini-project/README.md](file:///home/akshanshsinha/DevOps/devops-heros/session19-cloud-terraform/08-mini-project/README.md) for full project architecture and manifests.
