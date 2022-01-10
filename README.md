# packer_test
Hashicorp Packer Testing


## Validate the template
```sh
packer validate packer.json
```

## Update credentials
Update the `aws_access_key`, `aws_secret_key`, `aws_subnet_id`, and `aws_security_group` values in the `variables` section

## Run the build
```sh
packer build amazon/packer.json
```
