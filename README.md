# k8s-vsphere-install

## Requirements
- Ansible
- Terraform


## Usage

## Install requires Ansible roles

```sh
cd ansible
ansible-galaxy role install -r roles/requirements.yml
```


provision VMs on vSphere and run Ansible playbook to install Docker:

```sh
cd ../terraform
terraform apply
```


