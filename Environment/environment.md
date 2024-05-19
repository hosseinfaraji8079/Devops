# Environment Setup

## Vagrant & Packer

### ``Source: Vagrant Official Docs``
[https://developer.hashicorp.com/vagrant/install#Linux](https://developer.hashicorp.com/vagrant/install#Linux)


## Step 1
### ``wget -O- https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg``

## Step 2
### ``echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list``

