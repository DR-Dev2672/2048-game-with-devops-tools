
This is a 2048 game which is deployed using EKS(Elastic Kubernetes Service).

http://k8s-game2048-ingress2-cdca5672ea-490139654.us-east-1.elb.amazonaws.com
```

Steps involved in deploying this application are:-

1> Creating an AWS Account and Setting up IAM Users
2> Installing Kubectl locally
3> Install ekctl
4> aws cli installation
5> configure aws in our terminal
6> Create cluster using command
```
<img width="1900" height="786" alt="Screenshot 2026-01-21 041350" src="https://github.com/user-attachments/assets/f4f0387d-6d30-426f-9a19-7615ed3c39db" />
<img width="1867" height="779" alt="Screenshot 2026-01-21 041437" src="https://github.com/user-attachments/assets/76a0e5c8-860b-4eac-a15d-d9aefbf31ba9" />

```

7> Add fargate profile for authentication
```
<img width="1869" height="810" alt="Screenshot 2026-01-21 041658" src="https://github.com/user-attachments/assets/c77c9bfc-709e-4687-bb12-3318c051f1c2" />
```
8> Deploy the deployment,services,ingress
```
<img width="1870" height="815" alt="Screenshot 2026-01-21 041518" src="https://github.com/user-attachments/assets/b354d218-6efe-4ef8-81e5-656d5e245cfd" />
```
9> Configure IAM OIDC provider
10> Download IAM policy
11> Create IAM Policy
12> Create IAM Role
13> ADD helm repo
14> Update helm repo
15> Install aws load balancer
```
<img width="1878" height="804" alt="Screenshot 2026-01-21 041615" src="https://github.com/user-attachments/assets/e62edd76-58b8-45cf-9da5-8333b4827252" />
```
16> Verfiy deployment are running or not.
```
<img width="1880" height="962" alt="Screenshot 2026-01-21 045328" src="https://github.com/user-attachments/assets/4ff7b02f-8c0c-49f5-971b-6c4f56741387" />






