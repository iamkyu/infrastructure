# infrastructure

## Terraform
Install
```shell
$ brew install terraform
```

Simple
```shell
$ terraform init
$ terraform plan
$ terraform apply
```

Run with specify a variable file
```shell
$ terraform apply \
    -var-file="variables1.tfvars" \
    -var-file="varibales2.tfvars"
```
