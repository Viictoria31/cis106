---
Name: Erneldy Reynoso
Semestre: Fall 2023
Course: cis106
Instructor: H. Alberto
---


## What are the server hardware specifications (virtual machine settings)? Take a screenshot - don’t type it!

![q.1.1.png](Screenshot_1.png)
## What is Ubuntu server log in screen? Take screenshot - do not type it!
![q.1.2.png](Screenshot_3.png)

## What is the IP address of your Ubuntu Server Virtual Machine?
10.0.2.15
![q.1.3.png](Screenshot_4.png)

## How do you enable the Ubuntu Firewall?
sudo ufw enable
![q.1.4.png](Screenshot_5.png)

## How do you check if the Ubuntu Firewall is running?
sudo ufw status
![q.1.5.png](Screenshot_6.png)

## How do you disable the Ubuntu Firewall?
sudo ufw disable
![q.1.6.png](Screenshot_10.png)

## How do you add Apache to the Firewall?
sudo ufw allow 'Apache'

## What is the command you used to install Apache?
sudo apt install apache2 -y

## What is the command you use to check if Apache is running?
sudo systemctl status apache2 --no-pager
![q.1.7.png](Screenshot_7.png)

## What is the command you use to stop Apache?
sudo systemctl stop apache2 --no-pager

## What is the command you use to restart Apache?
sudo systemctl restart apache2 --no-pager
![q.1.8.png](Screenshot_8.png)

## What is the command used to test Apache configuration?
sudo apache2ctl configtest
![q.1.9.png](Screenshot_11.png)

## What is the command used to check the installed version of Apache? 
apache2 -v
![q.1.10.png](Screenshot_12.png)

## Which are Apache Log Files, and what are they used for? Provide examples and screenshots.
![q.1.10.png](Screenshot_9.png)
