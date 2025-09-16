# Apache Deployment with Vagrant + Bash

This project provisions a **CentOS 9 VM** with **Vagrant** and configures it using a **Bash script**.  
It installs and starts **Apache**, then deploys a custom `index.html` page.

---

## 🚀 What it does
- Spins up a CentOS 9 VM with Vagrant  
- Provisions the VM with Bash (`setup.sh`)  
- Installs and starts Apache  
- Deploys a custom webpage (`index.html`)  

---

## 🛠 How to Run
1. Clone this repo:
   ```bash
   git clone https://github.com/k-r-i-s-h-h/Devops-projects.git
   cd Devops-projects/apache-vagrant-deployment

2. vagrant up

3.  Access the webpage:

    Get the private IP from the Vagrantfile
    
    Open http://<private-ip> in your browser 
