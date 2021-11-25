# ec2-terraform-multiple-regions

steps to run :

1) terraform init : terraform init -backend-config=access_key="XXXXX" -backend-config=secret_key="XXXX"
2) terraform apply
3) ansible: ansible-playbook -i inventory  provision_frontend.yml --private-key=XXXX.pem --user ubuntu
