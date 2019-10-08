# hadoop_setup

Setup of ##Big Data Hadoop version 1

Following steps are required -
1)Fork and Download the repository on the machine where you need to set up hadoop.
2) You must have rpm of jdk and hadoop at a specified loaction on the target machine. The path can be edited in the var.yml file.
3) IP variable holds the ip of master node.
4) Correctly setup the hosts file for setting the namenode and datanode.
5) Run # ansible-playbook main.yml -i hosts
6) Go to your browser http://IP:50070

ENJOY!

