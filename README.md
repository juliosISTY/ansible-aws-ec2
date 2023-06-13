# ansible-aws-ec2

## Notes

Before running *ansible-playbook*, installed roles and export aws credentials with these commands:
```sh
ansible-galaxy install -r roles/requirements
export AWS_ACCESS_KEY_ID='value'
export AWS_SECRET_ACCESS_KEY='value'
```
Don't forget also to create devops.pem file for private key and put the correct path in group_vars/all.yml file.

