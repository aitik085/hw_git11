# hw_git11
## .gitignore

#### Игнорировать временные файлы логов с расширением .log   
*.log 

#### Игнорировать файл myconf
myconf

#### Игнорировать файлы которые находятся в директории .terraform/
.terraform/

#### Игнорировать файлы с расширением .tfstate
*.tfstate
#### Игнорировать любые файлы у которых имя начинается с .tfstate. и заканчивается любыми символами
*.tfstate.* 

#### Игнорировать файл crash.log
crash.log

#### Игнорировать файлы корые начинаются со слова crash., содержат любые символы (*) в середине и заканчиваются расширением .log
crash.*.log

####  Игнорировать файлы с расширением .tfvars  
*.tfvars
####  Игнорировать файлы с расширением .tfvars.json  
*.tfvars.json

#### Игнорировать файл override.tf
override.tf
#### Игнорировать файл override.tf.json
override.tf.json
#### Игнорировать файлы у которых имя заканчивается на _override.tf
*_override.tf 
#### Игнорировать файлы у которых имя заканчивается на _override.tf.json
*_override.tf.json

#### Игнорировать файл .terraform.tfstate.lock.info
.terraform.tfstate.lock.info

#### Игнорировать файл .terraformrc
.terraformrc
#### Игнорировать файл terraform.rc
terraform.rc

git commit -m "Initial gitlab"
