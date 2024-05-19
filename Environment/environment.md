# Environment Setup

## Vagrant & Packer

#### ``Source: Vagrant Official Docs``
[https://developer.hashicorp.com/vagrant/install#Linux](https://developer.hashicorp.com/vagrant/install#Linux)


### Step 1
<pre> wget -O- https://apt.releases.hashicorp.com/gpg | sudo gpg --dearmor -o /usr/share/keyrings/hashicorp-archive-keyring.gpg </pre>

### Step 2
<pre> echo "deb [signed-by=/usr/share/keyrings/hashicorp-archive-keyring.gpg] https://apt.releases.hashicorp.com $(lsb_release -cs) main" | sudo tee /etc/apt/sources.list.d/hashicorp.list </pre>

### Step 3
#### For Vagrant
<pre>
sudo apt update && sudo apt install vagrant
</pre>

#### For Packer 
<pre>
sudo apt update && sudo apt install packer
</pre>
