### Karamelized Cookbook

This cookbook was auto-generated by Karamel.
You can now use the cookbook in a cluster definition file.


When running kitchen, you need to enable jdk 1.8:

sudo su
update-alternatives --config java

(pick jdk 1.8)


and allow flink slaves to start:

cat /home/flink/.ssh/id_rsa.pub >> /home/flink/.ssh/authorized_keys
cat /home/spark/.ssh/id_rsa.pub >> /home/spark/.ssh/authorized_keys
