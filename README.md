## Windows Environment
```bash
echo Alais Terraform (tf, tfc, tfa & tfaa, tfd & tfda - DANGER, tfp, tft, tff, tfv)
doskey tf=terraform.exe $*
doskey tfi=terraform init $*
doskey tfc=terraform.exe validate
doskey tfa=terraform.exe apply
doskey tfaa="terraform.exe apply -auto-approve"
doskey tfd=terraform.exe destroy
doskey tfda="terraform.exe destroy -auto-approve"
doskey tfp=terraform.exe plan
doskey tft=terraform.exe taint $*
doskey tfv=terraform.exe version $*
doskey tff=terraform.exe fmt $*
echo Alias Clear (cls)
doskey clear=cls $*
```


# Mac / Linux Environments
```bash
alias tf=terraform
alias tfi="terraform init"
alias tfc="terraform validate"
alias tfa="terraform apply"
alias tfaa="terraform apply -auto-approve"
alias tfd="terraform destroy"
alias tfdd="terraform destroy -auto-approve"
alias tfv="terraform validate"
alias tff="terraform fmt"
alias tfv="terraform version"
```
