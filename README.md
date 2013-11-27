# Scala + Play2 Automated VM

A Vagrant box to get Play2 projects running instantly. 

Can also be used to quickly deploy a Play2 applications on EC2 or Digital Ocean.

## Use

```
vagrant up
vagrant ssh
cd /vagrant
sudo play new myapp
sudo play run

```

You should now be able to see your Play2 application running on http:33.33.33.10:9000
