
 ##### Command to run playbook
 ```bash
 ansible-playbook -i inventory/vm-setup-playbook/hosts.ini var.yml
```
 ##### Command to run playbook with run time variables
 ```bash
 ansible-playbook -i inventory/vm-setup-playbook/hosts.ini var.yml --extra-vars '{"version":"1.0","other_variable":"foo"}'
```
##### Passing file name in run time
```bash
 ansible-playbook -i inventory/vm-setup-playbook/hosts.ini var.yml --extra-vars "@my_vars.yml"
```
