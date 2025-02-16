# Collection of useful bash scripts for nix systems.

## Installer
 - script: installer.sh `you_chosen_option`
 - Description: Script to install some useful tools via Docker or apt-get
 - Keywords: "mongodb", "elasticsearch", "redis", "neo4j", "nginx", "nginx_certbot", "docker", "docker-compose"

## Toolkit
 - script: toolkit.sh
 - Description: Automate linux operations
 - Keywords: "disk mount", "fstab", "automount", "disk format", "ext4", "resize", "ssh-add"

 ## Performance tuning
 - script: perf_tuning.sh
 - Run script as sudo: 
        sudo ./perf_tuning.sh
 - Description: Parameter tuning for linux system for scaling
 - Keywords: "performance", "scale", "tuning" 

## GCP Firewall: 
 - script: gcloud_firewall.sh `your firewall rule name`
 - Description: Add your dynamic ip to firewall rules in gcp

## AWS Firewall: 
 - script: aws_firewall.sh `security group id` `security group rule id` `port number`
 - Description: Add your dynamic ip to security group in aws