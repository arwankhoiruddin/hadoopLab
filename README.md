# Introduction

This is to help students on lab session of Real Time Analysis Course in Universiti Teknologi PETRONAS, Malaysia 

# Lab Goal

The goal of the lab is to learn and practice Hadoop installation. The hadoop version used is Hadoop 3.2.2, while the OS used is Ubuntu 18.04 LTS on Google Cloud Platform (GCP)

# Prerequisite

## Get GCP Ready

* Input your billing. If you are new, you will get $300 for free that you can use in GCP
* Create your first VM. Use the closest server to you (Singapore) so it will be fast
* Ensure that https access is chosen
* You can use any OS if you like. However, to make our lab easy (for easy debug), we will use similar OS for our lab, i.e. Ubuntu 18.04 LTS

## Go to the VM via SSH

* You can use any SSH server (e.g. putty, terminal, etc)
* However, GCP provides a very convenient environment for accessing the VM. We can use just our browser! :D

## Install Java

Check if java is installed by running this command

```
java -version
```
If you find this:

```
Command 'java' not found, but can be installed with:
apt install default-jre            
apt install openjdk-11-jre-headless
apt install openjdk-8-jre-headless 
Ask your administrator to install one of them.
```

Then install it using the following command

```
sudo apt install default-jre
```

## Download Hadoop

### Run this in command

```
curl -o hadoop-3.2.2.tar.gz https://downloads.apache.org/hadoop/common/hadoop-3.2.2/hadoop-3.2.2.tar.gz
```

### Now extract 

```
tar xvfz hadoop-3.2.2.tar.gz
```

