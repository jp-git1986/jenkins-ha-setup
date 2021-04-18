# jenkins-ha-setup

This Github code is used to create a jenkins HA setup with 2 client masters and 1 ops center server

High - Level steps:

1) Mount AWS EFS on client masters and ops center for jenkins_home,jenkins_ops_center_home respectively
2) Install jenkins and plugins on primary client master and install jenkins on standby client master
3) Configure ops center in a dedicated server
4) Install slave agent and add the same to client master
