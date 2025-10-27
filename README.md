# hw_git11

### Будут игнорироваться в терраформовском гитигноре:
```
.terraform/ - Файлы которые находятся в директории ./Terraform. 
*.tfstate - Все файлы с расширением .tfstate
crash.log - Файл crash.log
crash.*.log - Файлы логов с дополнительными именами.
.terraform.tfstate.lock.info - Временный файл .terraform.tfstate.lock.info.
*.tfvars  - Файлы с расширением *.tfvars
*.tfvars.json - JSON-версии файлов *.tfvars.
override.tf - Файл override.tf 
override.tf.json JSON-версии файлов override.tf.
*_override.tf.json  - Файлы, локального переопределения конфигурации *_override.tf.json
.terraformrc - Файлы с раширением .terraformrc.  (Локальные файлы конфигурации для интерфейса командной строки Terraform.)
terraform.rc - Файл terraform.rc (Локальные файл конфигурации)
```