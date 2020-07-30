# docker-vsphere-install

## Requirements
- Ansible
- Terraform


## Usage

### Install requires Ansible roles

```sh
cd ansible
ansible-galaxy role install -r roles/requirements.yml
```


### Provision VMs on vSphere and run Ansible playbook to install Docker:

```sh
cd ../terraform
terraform apply
```


