# XCRI Cluster Monitoring Toolkit

Simple toolkit to install cluster monitoring software.

## Contents:

This includes ansible scripts to install Grafana, Prometheus and SLURM exporter on a Jetstream Virtual cluster. Once installed, Grafana portal can be accessed through http://head-node-ip:3000. 

## How to install

ansible-playbook --extra-vars "host=head-node-ip" clustermon.yml


This work supported by [![NSF-1548562](https://img.shields.io/badge/NSF-1548562-blue.svg)](https://nsf.gov/awardsearch/showAward?AWD_ID=1548562)
